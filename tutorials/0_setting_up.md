# Setting up your environment

Disclamer: these steps work on Linux, and usually on OSX. Windows is not yet supported. For updates on Windows support, see [this issue](https://github.com/william01110111/MyLang/issues/2).

1. Open a terminal and navigate to where you want the MyLang folder to go
2. Run the command `git clone https://github.com/william01110111/MyLang.git`. This will download the MyLang source code
3. Move into the MyLang directory
4. run the command `make`. If you get a _command not found_ error, you may need to install make or g++.
5. If all goes well, after a few seconds you should end up with a MyLang executable in your current directory called `MyLang`.
6. Run it with the command `./MyLang path/to/MyLang/source.pn`. If you don't have any MyLang source code yet, test it with `./MyLang examples/hello_world.pn`
7. If it works, you can now move on to the "basic concepts" tutorial

[index](index.md) | [next: Basic Concepts ->](1_basic_concepts.md)
