### In progress

As I am unable to find the source code for Android's (very useful!) systrace viewing tool,
I'm going to deobfuscate it and modify it to be a bit less massively hostile to use.

Ultimately my goal is to be able to host a single static file, and paste in the results from `adb
shell atrace` without further work.
