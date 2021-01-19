# anypasswd

This utility manages any password file.  
It supports the following formats.

- Basic Access Authentication
- Digest Access Authentication
- Apache AuthGroupFile
- ProFTPD password file
- ProFTPD group file
- Dovecot password file

## Setup

Copy the executable `anypasswd' to some directory in your PATH.

## Usage

Add or modify an account

    anypasswd [-c] /path/to/file username
  
Remove account(s)

    anypasswd -r /path/to/file username [username ...]

Display help

    anypasswd -h

## License

This software is released under the GNU General Public License Version 3, see LICENSE.

## Author

Taka Goto
