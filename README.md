**_cryptoGX_** - just another en- / decryption software

- [Introduction](#introduction)
- [Downloads](#Downloads)
- [Usage](#Usage)
- [License](#License)

# Introduction

**cryptoGX** is a java based software for en- / decrypting texts or files and secure delete files.
It was designed to be controlled with a GUI, but can also be used from the command line.

Because the GUI uses javaFX, java version from 1.8.0_40 to 10.* with javaFX support is required (also applies to windows .exe files).

# Downloads

| 1.11.0 |
|:-------|
| [Source code](https://github.com/blueShard-dev/cryptoGX/archive/master.zip) |
| [Executable jar file](https://dl.dropbox.com/s/1px5dotzyop3rpn/cryptoGX.jar?dl=0) |
| [Windows portable](https://dl.dropbox.com/s/10jf6cfpnejrvbf/cryptoGX_1.11.0_portable.exe?dl=0) |
| [Windows installer](https://dl.dropbox.com/s/lq9kuv4erv39y3n/cryptoGX_1.11.0_win_setup.exe?dl=0) |

**NOTE**: If you download one of the windows executables (`.exe`) your antivirus may scan the file(s)

# Usage

The `.jar` file can be started with and without arguments.
If it gets called without arguments the GUI will launch normaly.
If it gets called with arguments, the GUI won't launch. The usage of arguments are described below.

Command line arguments:
```
Usage AES:

    Text en- / decryption
        encrypt: <cryptoGX jar file> AES <key> <salt> encrypt <string>
        decrypt: <cryptoGX jar file> AES <key> <salt> decrypt <encrypted string>

    File en- / decryption
        encrypt: <cryptoGX jar file> AES <key> <salt> encrypt <path of file to encrypt> <encrypted file dest>
        decrypt: <cryptoGX jar file> AES <key> <salt> decrypt <encrypted file path> <decrypted file dest>

Secure delete file: <iterations> <path of file to delete>
```
or type `<cryptoGX jar file> -help` to get help

# License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for more details