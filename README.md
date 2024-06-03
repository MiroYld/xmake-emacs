# xmake-emacs

## Description

This is an integration of xmake for Emacs, allowing you to build, clean, and run projects directly from within Emacs.

## Features
- Build projects using xmake directly from Emacs.
- Clean projects using xmake clean.
- Run projects using xmake run with target extraction from xmake.lua.
- Stop the running process launched by xmake run.

## Prerequisites
- [xmake](https://github.com/xmake-io/xmake) must be installed on your system.

## Installation
1. Clone this repository or download the xmake.el file.
2. Copy xmake.el to your Emacs configuration directory or load it in your Emacs session.

## Usage

### Building the Project
To build the project, use the `M-x xmake-build` command or bind it to a key of your choice.

### Cleaning the Project
To clean the project, use the `M-x xmake-clean` command or bind it to a key of your choice.

### Running the Project
To run the project, use the `M-x xmake-run` command or bind it to a key of your choice. The target name will be extracted from the xmake.lua file in the project directory.

### Stopping the Running Process
To stop the process launched by `xmake run`, use the `M-x xmake-stop` command or bind it to a key of your choice.

## Roadmap and Contributing

- **Syntax Highlighting:** Implement syntax highlighting for xmake scripts to improve readability and ease of use.

- **Generation of compile_commands.json:** Add support for generating a `compile_commands.json` file to facilitate integration with IDEs and code editors.

- **Selection of Build Type (Debug/Release):** Implement functionality to choose between building in debug or release mode.

- **Multiple Targets Management:** Improve support for managing multiple targets in the project, allowing users to specify which target to build, clean, or run.

If you have ideas or would like to contribute to the project, please open an issue or submit a pull request.

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
