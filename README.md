# gdnative-downloader

This is a simple gdnative plugin that uses libcurl to download files.

## Building

This is a standard cmake project. It can either be built with command line or loaded directly in visual studio. Command line example is:

```
mkdir build
cd build
cmake ..
make
```

Output bins will be placed in the `project/gdnative` folder. Simply copy the gdnative folder into your current godot project to use it.


## Usage

An example project is located in the `project` folder, but the following shows basic usage:

