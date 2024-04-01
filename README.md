# UDP Communication Program

This program demonstrates a simple UDP server and client communication system. It supports basic message sending capabilities, file transfer (in certain configurations), and has the ability to handle multiple clients.

## Features

- UDP-based message exchange.
- Support for IPv4 and IPv6.
- Basic command handling (`/HELO`, `/QUIT`).
- (Optional) File transfer capabilities.
- (Optional) Support for multiple clients in a chat-like system.

## Requirements

- C compiler (e.g., GCC, Clang)
- Make (optional, for building with a Makefile if provided)

## Installation

Clone the repository to your local machine:

# UDP Communication Program

This program demonstrates a simple UDP server and client communication system. It supports basic message sending capabilities, file transfer (in certain configurations), and has the ability to handle multiple clients.

## Features

- UDP-based message exchange.
- Support for IPv4 and IPv6.
- Basic command handling (`/HELO`, `/QUIT`).
- (Optional) File transfer capabilities.
- (Optional) Support for multiple clients in a chat-like system.

## Requirements

- C compiler (e.g., GCC, Clang)
- Make (optional, for building with a Makefile if provided)

## Installation

Clone the repository to your local machine:


Compile the program using your C compiler. For example, with GCC:

gcc -o udp_communication main.c -D<FLAG> // Replace <FLAG> with BIN, USR, or FILEIO as needed.


## Usage

To run the server:

./udp_communication <port_number>


To run a client, use the same command on a different terminal or machine, ensuring the server is accessible.

## Commands

- `/HELO` - Initial handshake command from client to server.
- `/QUIT` - Command to gracefully exit the chat or server.

(Include any additional commands or instructions specific to file transfer or multi-client support here.)

## Contributing

Contributions are welcome! Please read the `CONTRIBUTING.md` for guidelines on how to submit pull requests, report issues, or request features.

## License

This project is licensed under the [MIT License](LICENSE). See the LICENSE file for details.

## Contact

For questions or support, please open an issue in the GitHub issue tracker for this repository.
