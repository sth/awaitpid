# awaitpid

Shell command to wait for other programs to terminate.

## Usage

The script takes one or more PIDs as parameters and waits for them to
terminate:

    awaitpid 123

This waits for process mit PID 123 to terminate.

### Options

- `-h`, `--help`: Show usage
- `-s`, `--sleep-interval=N`: Check the processes at least once every `N` seconds (default `0.5`)

## Installation

Simply copy `awaitpid` to a location in your `PATH`:

    sudo awaitpid /usr/local/bin/

