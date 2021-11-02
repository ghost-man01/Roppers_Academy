# File Descriptor

File descriptor in Unix/Linux Operating system is indicator of connection maintained by kernel to I/O operations. *In windows-file based system it’s called **filehandle***

By default there are three types of descriptors in Linux :

1. Data Stream for Input
- `STDIN - 0`
1. Data Stream for Output
- `STDOUT - 1`
1. Data Stream for Output that relates to an error occurring.
    - `STDERR - 2`

**/dev/null** – It’s null a *null device* which discards all data.