# Kit

Kit is a basic version control system (VCS) built using JavaScript. It provides essential functionalities to manage and track changes in your projects.

## 📚 Table of Contents

- [Features](#-features)
- [Getting Started](#-getting-started)
- [Installation](#-installation)
- [Usage](#-usage)
  - [Initialize a Repository](#-initialize-a-repository)
  - [Track Changes](#-track-changes)
  - [Commit Changes](#-commit-changes)
  - [View Commit Logs](#-view-commit-logs)
  - [Show Commit Differences](#-show-commit-differences)
- [License](#-license)

## 🚀 Features

- 🆕 Initialize a new repository
- 📂 Track changes to files
- 📝 Manage commits and logs
- 🔍 Show differences between commits
- 📜 View the content of a specific commit

## 🏁 Getting Started

To get started with Kit, follow these steps:

1. **Install Kit**: Follow the installation instructions above to clone the repository and install dependencies.
2. **Initialize a Repository**: Use the `./kit.mjs init` command to create a new repository.
3. **Track Changes**: Add files to the repository using the `./kit.mjs add <file>` command.
4. **Commit Changes**: Commit your changes with a message using the `./kit.mjs commit "Your commit message"` command.
5. **View Logs and Differences**: Use `./kit.mjs log` to view commit logs and `./kit.mjs show <commitHash>` to see differences between commits.

By following these steps, you can start managing your project's version control with Kit.

## 📦 Installation

To install Kit, clone the repository and install the dependencies:

```bash
git clone https://github.com/anuja-rahul/kit-vcs-js.git
cd kit-vcs-js
npm install
```

## 🛠️ Usage

### 🏁 Initialize a Repository

To initialize a new Kit repository, run the following command:

```bash
./kit.mjs init
```

This will create a `.kit` directory in your project with the necessary files and directories.

### 📈 Track Changes

To track changes in your project, use the following command:

```bash
./kit.mjs add <file>
```

### 💾 Commit Changes

To commit changes, use the following command:

```bash
./kit.mjs commit "Your commit message"
```

### 📜 View Commit Logs

To view the commit logs, use the following command:

```bash
./kit.mjs log
```

### 🔍 Show Commit Differences

To show the differences between commits, use the following command:

```bash
./kit.mjs show <commitHash>
```

## 📄 License

This project is licensed under the [MIT License](LICENSE).
