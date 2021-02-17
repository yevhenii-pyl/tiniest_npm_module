# yev.pyl/tiny_package

![npm](https://img.shields.io/npm/v/@yev.pyl/tiny_package)

It's the tiniest module I can imagine. Works like an ES module. 

import {tiny} from "@yev.pyl/tiny_package"

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
