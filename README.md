# Setting Up Your Developer Environment

## Objective:
This document provides a comprehensive guide to setting up an efficient developer environment for software engineering projects, including installation and configuration of necessary tools and software.

## Tasks:

### 1. Select Your Operating System (OS):

#### Download and Install Windows 11:
1. Visit the [Windows 11 download page](https://www.microsoft.com/software-download/windows11).
2. Follow the instructions on the page to download and install Windows 11.

### 2. Install a Text Editor or Integrated Development Environment (IDE):

#### Download and Install Visual Studio Code:
1. Visit the [Visual Studio Code download page](https://code.visualstudio.com/Download).
2. Download the installer for your operating system.
3. Run the installer and follow the setup instructions.

### 3. Set Up Version Control System:

#### Install Git:
1. Visit the [Git download page](https://git-scm.com/downloads).
2. Download the installer for your operating system.
3. Run the installer and follow the setup instructions.

#### Configure Git:
1. Open a terminal or command prompt.
2. Set your username:
   ```bash
   git config --global user.name "Your Name"
   ```
3. Set your email:
   ```bash
   git config --global user.email "your-email@example.com"
   ```

#### Create a GitHub Account:
1. Visit [GitHub](https://github.com).
2. Sign up for a new account or log in if you already have one.

#### Initialize a Git Repository:
1. Create a new directory for your project:
   ```bash
   mkdir my_project
   cd my_project
   ```
2. Initialize a new Git repository:
   ```bash
   git init
   ```
3. Create a README file and make your first commit:
   ```bash
   echo "# My Project" >> README.md
   git add README.md
   git commit -m "Initial commit"
   ```

### 4. Install Necessary Programming Languages and Runtimes:

#### Install Python:
1. Visit the [Python download page](http://www.python.org).
2. Download the installer for your operating system.
3. Run the installer and follow the setup instructions.

#### Verify Python Installation:
1. Open a terminal or command prompt.
2. Check the Python version:
   ```bash
   python --version
   ```

### 5. Install Package Managers:

#### Install pip:
1. `pip` is included with Python 3.4 and later. Verify `pip` installation:
   ```bash
   pip --version
   ```

### 6. Configure a Database (MySQL):

#### Download and Install MySQL:
1. Visit the [MySQL download page](https://dev.mysql.com/downloads/windows/installer/5.7.html).
2. Download the MySQL Installer.
3. Run the installer and follow the setup instructions.

### 7. Set Up Development Environments and Virtualization (Optional):

#### Install Docker:
1. Visit the [Docker download page](https://www.docker.com/products/docker-desktop).
2. Download Docker Desktop for your operating system.
3. Run the installer and follow the setup instructions.

### 8. Explore Extensions and Plugins:

#### Visual Studio Code Extensions:
1. Open Visual Studio Code.
2. Go to the Extensions view by clicking the square icon in the sidebar or pressing `Ctrl+Shift+X`.
3. Search for and install the following extensions:
   - Python (by Microsoft)
   - GitLens (by GitKraken)
   - Prettier - Code formatter (by Prettier)


#### Challenges Faced during installation
1. **Installing Git:**
   - Encountered issues with environment variables not being set correctly.
2. **MySQL Configuration:**
   - Faced difficulties with setting up the correct user permissions.

#### Solutions Employed:
1. **Installing Git:**
  
   - Resolved by manually adding Git to the system PATH.
2. **MySQL Configuration:**
   - Followed online tutorials and documentation to properly configure user permissions and set up a test database.

