# Royaloakap
--Author=Royaloakap--

Quick start guide for your C2 project

This README provides instructions for getting started with this Go project, including compiling and running the source code. This project is structured around several .go files, each with a specific role in the application.

Features Active and not active.

- [x] Secure Shell CNC Base
- [ ] Command System
- [ ] API System
- [x]Gradient Generator
- [ ] Ban System
- [ ] Kick System
- [x]User System
- [x] Database
- [x]Attack System

<h3>⚡️ Current Features: ⚡️</h3>

- Secure shell based command and control.
- Argon2 hashed passwords
-Basic Logs
-Basic switch theme




Prerequisites
Make sure you have Go installed on your system. To check if Go is already installed, open a terminal and type:

bash
Copy code
go version
If Go is not installed, follow the installation instructions on the official Go website.

Project structure
The project contains the following files and folders:

main.go: The application entry point.
admin.go: Manages administrative features.
attack.go: Contains code to simulate or perform attacks.
database.go: Manages interactions with the database.
gradient.go: Provides additional utilities (for example, for data processing or user interface).
ssh/: A folder containing SSH-related scripts or configurations.
go.mod: A file that describes the module's dependencies.
README.md: This file, which provides information and instructions about the project.
Compilation and execution
To compile and run the project, follow these steps:

Open a terminal and navigate to the directory containing your source code.

bash
Copy code
cd path/to/your/project
Compile the project using the go build command. This command will compile the source files into an executable based on the main.go file.

bash
Copy code
go build -o name_of_your_executable main.go
Replace name_of_your_executable with the name you want to give to the generated executable.

Run the generated executable:

bash
Copy code
./name_of_your_executable
Dependency management
If your project depends on external libraries, they should be defined in go.mod. To download the dependencies specified in go.mod, run:

bash
Copy code
go mod tidy
This will download and install the dependencies required for your C2 project.

Contribution and support
To contribute to this project, please follow the contribution guidelines set by the maintainer. For support, open an issue on the project's GitHub page or contact the maintainer directly.

By following these instructions, you should be able to compile and run your C2 project in Go. For any additional questions, please contact @royaloakap on telegram or on discord! (t.me/royal_faq), (discord.gg/royalc2).