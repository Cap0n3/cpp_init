# cpp_project_init

This script is designed to initialize a C++ project with a basic directory structure.

## Usage

```bash
./cpp_project_init.sh
```

Once the script finishes, your C++ project will be initialized with the following structure:

```
c++_project/
├── bin/
├── doc/
├── include/
├── lib/
├── src/
└── test/
```

Here's a brief description of each directory:

- `bin`: Compiled binaries
- `doc`: Documentation files
- `include`: Header files
- `lib`: External libraries
- `src`: Source code
- `test`: Test files

## Optional parameters

- `--help ` - Display help
- `--vscode` - Open VS Code after creating the project structure with a boilerplate `tasks.json` file.
