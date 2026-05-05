# Flutter-Dev-Container

## Features

- Requires only the `ms-vscode-remote.remote-containers` extension in VS Code to get started.  
- Supports USB device mounting, making it easy to test projects on real devices.  

> [!TIP]  
> Intended for **development environments only**.  
> For CI/CD setup, refer to [Continuous delivery with Flutter](https://docs.flutter.dev/deployment/cd).

## Install

```bash
git clone --filter=tree:0 --depth=1 --no-tags https://github.com/XIAN-SHENG-576692/Flutter-Dev-Container.git
```

## File Structure

- `.devcontainer/`: The configuration files for `ms-vscode-remote.remote-containers` extension in VS Code to build the container.
- `dev/`: Some scripts for developer. 

## Scripts in `dev/`

### [`preinstall_android_sdk.sh`](dev/preinstall_android_sdk.sh)

- To prevent **out-of-memory** errors.
- To ensure `dart-code.flutter` can detect Android devices over USB.

> [!CAUTION]  
> The script **must be executed inside the container**.
