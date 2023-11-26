# 🔥 Pre-Requisites & Initial Setup For Backend

The purpose of this file is to document the pre-requites and initial setup before setting up Backend Application.

According to our scope, Python 3 is used for serving the API Endpoints and Backend services for web & cloud-based applications.

Please make sure you have all the following installed on your own machine.

> <b>Note</b> : <span style="color: #FF9A23">This document is subject to be refactored/updated based on the technical documentation of the specific tools/packages.</span>

## ✅ Python 3 Installation

### 👉🏻 For Windows OS Users

1. Visit the official Python Website : https://www.python.org/downloads/
2. Select the Latest Version of Python 3 for Windows to download.
3. Once the Python Installer is downloaded, double click it and run it.
4. Check the box &#9745; that says `Add Python to PATH` during installation to make Python easily accessible from the command line.
5. Follow the on-screen instructions to complete the installation.

### 👉🏻 For MacOS Users

You can install Python using `Homebrew` or by directly downloading the Python installer from the Python Official Website.

#### - Using Homebrew

1. Open your terminal.
2. Check whether `Homenrew` is installed in your local machine with the help of the following command. The below command will check the version of `Homebrew` in your local machine.

```sh
brew -v
```

3. [<b>Optional</b>] If `Homenrew` is not installed in your local machine, install it by following the instructions on the [Homebrew Website](https://brew.sh/).

4. After successfully installing `Homenrew`, run the following command to install Python 3.

```sh
brew install python3
```

#### - Using Python Installer

1. Visit the official Python Website : https://www.python.org/downloads/
2. Download the latest version of Python 3

![Python Website](/images/python-downloads.png)

3. Run the MacOS Installer (`.pkg`) file and follow the On-Screen Instructions to install Python 3.

### 👉🏻 For Linux OS Users

The steps to install Python 3 can vary depending on your distribution. Below are intructions for 2 common package managers `apt` (Debian/Ubuntu) and `dnf` (Red Hat/Fedora). You can adapt these instructions to your specific distribution's package manager.

#### <b>Using `apt` (Debian/Ubuntu)</b>

1. Open your terminal
2. Update the package list to ensure you have the latest information

```sh
sudo apt update
```

3. Install Python3

```sh
sudo apt install python3
```

#### <b>Using `dnf` (Red Hat/Fedora)</b>

1. Open your terminal
2. Install Python3

```sh
sudo dnf install python3
```

## ✅ Python3 Version Confirmation

After successful installation, verify Python 3 by confirming the version in the terminal.

```sh
python3 --version
```

or

```sh
python3 -V
```

## ✅ `pip3` Installation

### 👉🏻 For Windows OS Users

1. Download the `get-pip.py` script from https://bootstrap.pypa.io/get-pip.py

2. Open the Windows Command Prompt and navigate to the folder where `get-pip.py` is downloaded.

3. Run the following command : 

- If you have only 1 Version of Python installed on your own machine : 

```sh
python get-pip.py
```

- If you have multiple versions of Python installed on your own machine (**Recommended**) : 

```sh
python3 get-pip.py
```

### 👉🏻 For MacOS Users

#### - Using Homebrew

1. Open your terminal.
2. Check whether `Homenrew` is installed in your local machine with the help of the following command. The below command will check the version of `Homebrew` in your local machine.

```sh
brew -v
```

3. [<b>Optional</b>] If `Homenrew` is not installed in your local machine, install it by following the instructions on the [Homebrew Website](https://brew.sh/).

4. After successfully installing `Homenrew`, run the following command to install Python 3.

```sh
brew install python3
```

Once you install Python 3 using Homebrew, then Pip3 should be available.

### 👉🏻 For Linux OS Users

The steps to install Pip3 can vary depending on your distribution. Below are intructions for 2 common package managers `apt` (Debian/Ubuntu) and `dnf` (Red Hat/Fedora). You can adapt these instructions to your specific distribution's package manager.

#### <b>Using `apt` (Debian/Ubuntu)</b>

1. Open your terminal
2. Update the package list to ensure you have the latest information

```sh
sudo apt update
```

3. Install Pip3

```sh
sudo apt install python3-pip
```

#### <b>Using `dnf` (Red Hat/Fedora)</b>

1. Open your terminal
2. Install Pip3

```sh
sudo dnf install python3
```

Once you install Python 3, then Pip3 should be available.

## ✅ `pip3` Version Confirmation

After successful installation, verify `pip3` by confirming the version in the terminal.

```sh
pip3 --version
```