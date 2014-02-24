Dart Syntax Highlighting
============================

Sublime Text 2 Dart plugin.

For 64-bit linux, install GNU Standard C++ Library 32 bit:

    sudo apt-get install lib32stdc++6

Download the Dart SDK here: http://www.dartlang.org/docs/getting-started/sdk/

Open the **Dart** folder in the **Packages** folder.

Open **Dart.sublime-build** file and change this part:

    "cmd": ["/home/adam/dart-sdk/bin/frogc", "$file"],

to your path to the dart-sdk folder
