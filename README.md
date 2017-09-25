# Unity Openr

Unity Openr is an open source project, created to open multiple Unity3D instances on MacOS.

**IF THIS IS YOUR FIRST TIME OPENING THE SOFTWARE YOU'LL NEED TO EXECUTE BY PRESSING CTRL WHILE CLICKING THE APP, THIS WILL GIVE THE PERMISION TO RUN IT**

### Requirements

This project is using a third party script, "appify", created by [mathiasbynens]: https://gist.github.com/mathiasbynens/674099

You'll need this script in order to compile your shell script into an .app application.

### Compile

Download the files in this repository. Navigate to it using the terminal. When you find the project root execute the command:

```sh
$ ./appify openunity.sh "Unity Openr"
```

In order to give your application permission you'll need to execute this command after:

```sh
$ chmod 744 Unity\ Openr.app
```

License
----

The MIT License (MIT)

Copyright (c) 2013 Thomas Park

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [mathiasbynens]: <https://gist.github.com/mathiasbynens>
