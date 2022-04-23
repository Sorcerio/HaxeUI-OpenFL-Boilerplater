# HaxeUI Boilerplate
>
> Boilerplate code for creating a HaxeUI Application.
>

## Requirements
* [Haxe](https://haxe.org/download/) (4.2.5)
* [OpenFL](https://www.openfl.org/download/) (9.1.0)
* [HaxeUI Core](http://haxeui.org/getting-started/installing-haxeui/) (1.4.0)
* [HaxeUI Backend: OpenFL](http://haxeui.org/getting-started/haxeui-openfl/) (1.4.0)

## Usage
1. Clone this repository.
1. Modify the `application.xml` file to suite.
    * Primary fields are the `<app ... />` and `<meta ... />` elements.
1. Use the build in VSCode tasks to build.
    * To build as HTML5, use `openfl test html5`.
    * To build as C++, use `openfl test cpp`.
    * Other targets can be configured as long as support is installed.

## Distribution
When distributing the C++ compilation of the project, the executable can be found at `./out/openfl/<operating_system_name>/bin`.
