# Winshell

Welcome to **Winshell**! This is a custom desktop environment that allows users to interact with applications directly from a simplified taskbar and desktop interface. Winshell provides the ability to run both console and Windows applications seamlessly, offering various features to manage and interact with running programs.

## Requirements

- **Windows OS**: The application is designed to run on Windows systems.
- **.NET Framework 9.0 or higher**: Make sure your system has the necessary .NET runtime.
- **.NET 6** for running and building the source code.
- **Administrator privileges** might be required for certain operations such as application embedding.

## Installation

### Download Version

1. Download the latest release from the [Releases](https://github.com/bardia-amjadi/Winshell/releases) section.
2. Extract the contents to your preferred directory.

### Setup from Shell

3. Launch `Shell\Shell.exe` outside of desktop
1. Write this code:
    ```bash
    set storage in [Your storage path]
    #for example 'set storage D:\Winshell\Storage' 
    ```
2. [Your storage path] means where is registries are installed
3. Run the code
4. Run the `Winshell.exe`

## Usage

### Running Applications

- **Console Apps**: Open console-based applications (like command-line tools) directly from the taskbar or panel.
    - Click on the application name in the taskbar to switch, minimize, or close it.
- **Windows Apps**: Open full Windows applications by selecting them from the taskbar or panel. Apps are embedded within the panel for seamless multitasking.
  
### Hotkeys

- **Alt + F1**: Launch the Runtime Manager.
- **Alt + F2**: Launch the Task Manager.
- **Alt + F3**: Open File Explorer.
- **Alt + F5**: Open the Log Manager.
- **Alt + F6**: Run the Shell console application.

### Taskbar and Panel

The taskbar allows you to manage applications as they run. You can:
- **Switch to** a running application.
- **Close** an application completely.
- **Minimize, Maximize, or Restore** the application window directly from the taskbar.

Each running application appears as a menu item in the taskbar, with a dropdown that provides the actions mentioned above.

## Contributing

This project is not currently open for contributions, but feedback and feature requests are always welcome.

## License

This project is licensed under the Epic Llama License

## Acknowledgements

- **System Windows API**: Used for window manipulation and embedding.
- **.NET Framework**: Essential for application development.
- **GitHub**: For hosting and collaboration.

## Support

If you have any questions or need help with Winshell, feel free to open an issue in the repository, or reach out to us directly via 'bardia.amjadi88@gmail.com'

---

Enjoy using Winshell, and thank you for exploring our custom desktop environment!

