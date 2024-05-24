# Rust Port Scanner

This is a simple, multithreaded port scanner written in Rust.

## Features

- Multithreaded scanning
- Supports both IPv4 and IPv6 addresses
- Customizable number of threads

## Usage

You can specify the IP address and the number of threads to use for scanning:

```bash
cargo run -- -j <number_of_threads> <ip_address>
```

If you don't specify the number of threads, the program will use 4 threads by default.

You can also get help:

```bash
cargo run -- -h
```

or

```bash
cargo run -- -help
```

## Output

The program will print out the open ports in ascending order.

## Disclaimer

This tool is for educational purposes only. Don't use it for illegal activities. Always obtain proper authorization before scanning networks.
