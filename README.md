# OpenJK Tools

SDK tools for Jedi Academy and Jedi Outcast released by Raven Software, under
the GNU GPLv2 license.


## Building the code

IBIze is being built using CMake and generated Makefiles. This works on all
platforms, including Windows, Linux and MacOS.

ModView and Assimilate are Visual Studio projects and as such only work on
Windows.


### Windows

Generate the project files either by following the Linux and macOS instructions
or by using the CMake GUI. For the CMake GUI, the source directory should be the
`ibize` directory in this repository. The build directory is a directory of your
choice where the project files will be generated, e.g. `ibize/build/`.

Load the generated project file (likely to be a Visual Studio project), and
then build in the IDE.


### Linux and macOS

Generate the makefiles (for IBIze only) by running:
```bash
cd ibize
mkdir build
cd build
cmake ..
```

Compile the code, while being in `ibize/build/`:
```bash
make
```


## Licensing

The OpenJK tools are licensed under GNU General Public License 2. See LICENSE
for more information.
