# IntelliJ IDEA Installation Guide for Linux Private Instance on AWS

This repository provides a step-by-step guide for installing IntelliJ IDEA on a Linux private instance hosted on AWS.

## Overview

This guide walks you through the process of installing IntelliJ IDEA on a Linux private instance. By following these steps, you'll be able to download IntelliJ IDEA, extract the files, and set up the environment to run the program.

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Installation Instructions](#installation-instructions)
3. [Usage](#usage)
4. [Additional Documentation](#additional-documentation)
5. [Contributing](#contributing)
6. [License](#license)

## Prerequisites

Before you begin, ensure you have:

- Access to an AWS private instance via SSH.
- Basic knowledge of Linux commands.

## Installation Instructions

1. **Download IntelliJ IDEA**:
   - Visit the [IntelliJ IDEA website](https://www.jetbrains.com/idea/).
   - Click "Linux".
   - Choose the .tar.gz file and click "Download".

2. **Download and Extract Files**:
   - SSH into your private instance.
   - Run the command `sudo wget <download_url>` to download the .tar.gz file to the `/opt` folder.
   - Extract the downloaded file using the command:
     ```
     tar -xzvf <file_name.tar.gz>
     ```
     Replace `<file_name.tar.gz>` with the name of the downloaded file.

3. **Run IntelliJ IDEA**:
   - Navigate to the extracted folder.
   - Locate the `idea.sh` script file in the `/bin` directory.
   - Run the command `./idea.sh` to execute IntelliJ IDEA.

4. **Enable GUI Environment**:
   - If you encounter the error "unable to detect the graphical environment", you need to enable the Linux GUI version.
   - Run the necessary command to enable the GUI environment and execute the `idea.sh` script again.

## Usage

Follow the provided instructions to install and run IntelliJ IDEA on your Linux private instance hosted on AWS.

## Additional Documentation

For more detailed instructions and additional resources, please refer to the [documentation folder](Documentation/) in this repository. The documentation includes PDF files with detailed guides, best practices, and exercises for practicing.

## Contributing

Contributions to this repository are welcome! If you find issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
