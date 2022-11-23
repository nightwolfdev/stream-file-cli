# Stream File

CLI to demonstrate how to read, write, and copy files using streams.

## Getting Started

1. Install [Node.js](https://nodejs.org/)
2. Clone the repo  
  `git clone https://github.com/nightwolfdev/stream-file-cli.git`
2. Navigate to the project folder  
  `cd stream-file-cli`

## Usage

`./stream-file <command> <path_to_file>`

- &lt;command&gt; can be:
  - **read**: Print the file's contents to the terminal
  - **write**: Write a message from the terminal to a file
  - **copy**: Create a copy of a file in the current directory
- &lt;path_to_file&gt; is the path to the file you want to work with

### Examples

- Read a file: `./stream-file read lorem-ipsum.txt`
- Write a file: `./stream-file write test.txt`
- Copy a file: `./stream-file copy lorem-ipsum.txt`

### Permission Denied Error

If you cannot run the program due to a **Permission denied** error, run the following command to provide the file with executable permissions: `chmod +x stream-file`.