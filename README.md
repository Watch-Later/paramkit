# ParamKit
[![Build status](https://ci.appveyor.com/api/projects/status/dw7xwgd9isgvsair?svg=true)](https://ci.appveyor.com/project/hasherezade/paramkit)

A small library helping to parse commandline parameters (for Windows).

[Docs](https://hasherezade.github.io/paramkit/) 📚

Objectives
-

+ "like Python's `argparse` but for C/C++"
+ compact and minimalistic
+ easy to use
+ extendable


Demo
-

Print help for each parameter:

<img src="https://raw.githubusercontent.com/hasherezade/paramkit/master/img/demo_help.png" alt="demo: print help" >

Paramkit allows you to add custom groups. You can use predefined, popular parameter types, or add your custom ones.

Easily parse and store values, and verify if all required parameters are filled:

<img src="https://raw.githubusercontent.com/hasherezade/paramkit/master/img/demo_print.png" alt="demo: print filled params" >

Verify if no invalid parameter was passed, and eventually suggest similar parameters:

<img src="https://raw.githubusercontent.com/hasherezade/paramkit/master/img/demo_invalid_param.png" alt="demo: print invalid param" >

See [the demo code](https://github.com/hasherezade/paramkit/tree/master/demo)
