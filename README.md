# Rust File Compression

This Rust project contains a command-line application that compresses a file using gzip compression. The application takes two command-line arguments: the source file to be compressed and the target file where the compressed data will be saved.

## Features

- Reads a source file
- Compresses the file using gzip
- Writes the compressed data to a target file
- Prints the original and compressed file sizes
- Measures and prints the time taken for compression

## Usage

### Prerequisites

- [Rust](https://www.rust-lang.org/) must be installed on your system. You can install Rust using `rustup`:

```sh
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
