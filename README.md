# Flutter-Dev-Container

## ✨ Features

- Requires only the `ms-vscode-remote.remote-containers` extension in VS Code to get started.  
- Supports USB device mounting, making it easy to test projects on real devices.  
- Includes helper scripts (⚠️ these must be run **inside the container**):  
  - [`preinstall_android_sdk.sh`](preinstall_android_sdk.sh): Installs required Android SDK components (`build-tools`, `cmake`, `ndk`, `platform-tools`, and `platforms`) in advance to prevent **out-of-memory** errors and ensure `dart-code.flutter` can detect Android devices over USB.  

> [!TIP]  
> Intended for **development environments only**.  
> For CI/CD setup, refer to [Continuous delivery with Flutter](https://docs.flutter.dev/deployment/cd).  
