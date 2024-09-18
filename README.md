# Express TypeScript Project Setup

This C++ program sets up a basic structure for a TypeScript Express application. It creates necessary directories and configuration files to kickstart your project quickly.

## Features

- Interactive and non-interactive project initialization
- Creates a project directory with the following structure:
  - `src/` - Source code directory
  - `routes/` - Directory for route definitions (optional)
  - `views/` - Directory for view definitions (optional)
- Generates essential configuration files:
  - `package.json`
  - `.env`
  - `tsconfig.json`
- Supports Windows and Unix-like operating systems

## Requirements

- C++17 or later
- A C++ compiler (e.g., g++, clang++)
- CMake (optional, for building)

## Usage

### Build the Program

1. Clone the repository:
   ```bash
   git clone https://github.com/shovan04/ExpressTs/blob/main/README.md <project name>
   cd <project name>
   ```

2. Compile the program:
   ```bash
   g++ -std=c++17 -o ExpressTs main.cpp
   ```

### Initialize a New Project

You can initialize a new project using the following commands:

#### Interactive Mode

```bash
./ExpressTs init
```
- You will be prompted to enter the project name and whether to use router-view.

#### Non-Interactive Mode

```bash
./ExpressTs -y
```
- This will create a project in the current directory.

### Project Structure

After initialization, the following structure will be created:

```
your_project/
│
├── .env
├── package.json
├── tsconfig.json
└── src/
    ├── index.ts
    ├── routes/
    │   ├── index.ts
    │   └── hello.route.ts
    └── views/
        └── hello.view.ts
```

## Getting Started

1. Navigate into your project directory:
   ```bash
   cd your_project
   ```

2. Install dependencies:
   ```bash
   yarn  # or npm install
   ```

3. Start the development server:
   ```bash
   yarn dev  # or npm run dev
   ```

4. Your server will be running at `http://localhost:8090/api/v1/hello/`.

## Contributing

Feel free to submit issues and pull requests. Contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
