# Ansible Practices

This repository uses Ansible for configuration management to automate and manage tasks on a test virtual machine (VM).  
Each topic or concept is developed in a dedicated branch (for example: `topic/file-module`, `topic/handlers`, etc.), allowing for focused, practical exercises.

---

## Environment Setup

This project uses Pipenv to manage Python dependencies.  
Alternatively, you can use a standard Python virtual environment.

### 1. Create a virtual environment
```bash
pipenv --python 3.13
```

### 2. Activate the environment
```bash
pipenv shell
```

### 3. Install dependencies
```bash
pipenv install ansible-core ansible-lint
```

**Note**: Make sure your local env has ssh access to your managed nodes.
**Note**: Make sure customizing your own `inventory.ini` file.
