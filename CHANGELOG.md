# Changelog

## v1.1.14
New feature: `--follow` option to stream logs in real-time. This is a game-changer for debugging and monitoring. Improved goroutines to fetch logs from multiple pods/containers simultaneously. Faster. 🔥
## v1.1.13

Support for parallel log fetching. Fetch logs from multiple pods/containers simultaneously. This enhances efficiency when dealing with large-scale deployments. Show log size.

## v1.1.12

Faster. 🔥 Use "bufio" to read logs in chunks instead of line by line. This is especially useful when reading large logs. Removed the "--reverse" option as it is just overhead now.

## v1.1.11

Added "--since" option to fetch logs newer than a relative duration. Added "--tail" option to get only the specified number of lines from the end of the logs.

## v1.1.10

Added "--all" option to get all logs in current namespace.

## v1.1.9

Added "--reverse" option to write logs in reverse order (date descending)

## v1.1.6

pass BuildVersion from the build system

## v1.1.1

Initial public release
