# gocat 🐱‍👤

![gocat](https://img.shields.io/badge/gocat-v1.0.0-blue.svg)
![GitHub repo size](https://img.shields.io/github/repo-size/gabrielgligdev/gocat)
![GitHub issues](https://img.shields.io/github/issues/gabrielgligdev/gocat)
![GitHub stars](https://img.shields.io/github/stars/gabrielgligdev/gocat?style=social)

## Overview

**gocat** is a modern, cross-platform alternative to the classic netcat tool, built using Go. It offers enhanced features for network communication, debugging, and security testing. Whether you are a developer, a network engineer, or a penetration tester, gocat provides the tools you need to effectively manage and troubleshoot your network.

## Features

- **Cross-Platform Compatibility**: gocat runs on various operating systems, including Windows, macOS, and Linux.
- **TCP and UDP Support**: Easily switch between TCP and UDP protocols for your network communication needs.
- **Port Scanning**: Quickly scan for open ports on a target machine.
- **Data Transfer**: Send and receive data over the network with simple commands.
- **Enhanced Security Testing**: Utilize gocat for penetration testing to identify vulnerabilities in your network.
- **User-Friendly CLI**: A straightforward command-line interface makes it easy to use.

## Installation

To get started with gocat, you can download the latest release from the [Releases section](https://github.com/gabrielgligdev/gocat/releases). Follow these steps:

1. Visit the [Releases section](https://github.com/gabrielgligdev/gocat/releases).
2. Download the appropriate binary for your operating system.
3. Extract the downloaded file.
4. Execute the binary from your command line.

## Usage

### Basic Commands

Here are some basic commands to help you get started with gocat:

- **Start a TCP listener**:

  ```bash
  gocat -l -p 8080
  ```

- **Connect to a TCP server**:

  ```bash
  gocat <server-ip> -p 8080
  ```

- **Send a message**:

  ```bash
  echo "Hello, World!" | gocat <server-ip> -p 8080
  ```

- **Port scan**:

  ```bash
  gocat -scan <target-ip>
  ```

### Advanced Features

gocat also supports advanced features for users who need more control over their network interactions.

- **UDP Communication**:

  To use UDP instead of TCP, simply add the `-u` flag:

  ```bash
  gocat -u -l -p 8080
  ```

- **Custom Payloads**:

  You can send custom payloads by specifying a file:

  ```bash
  gocat <server-ip> -p 8080 < payload.txt
  ```

- **Verbose Mode**:

  Use the `-v` flag for more detailed output during execution:

  ```bash
  gocat -v <server-ip> -p 8080
  ```

## Contributing

We welcome contributions to gocat! If you have suggestions, bug reports, or want to add features, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your forked repository.
5. Open a pull request.

## License

gocat is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- Special thanks to the Go community for their support and contributions.
- Thanks to the developers of netcat for inspiring this project.

## Support

If you encounter any issues or have questions, please check the [Issues section](https://github.com/gabrielgligdev/gocat/issues) or reach out to the community.

## Future Plans

We plan to continue enhancing gocat with more features, including:

- Improved error handling.
- GUI support for users who prefer a graphical interface.
- Integration with other security tools.

Stay tuned for updates!

## Conclusion

gocat is a powerful tool for anyone involved in network communication and security. With its modern design and robust features, it serves as an essential resource for developers and network professionals alike. Download it today from the [Releases section](https://github.com/gabrielgligdev/gocat/releases) and start exploring its capabilities.