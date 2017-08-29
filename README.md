# FLTK-1.3.4-1-user-examples-API
Examples and documents for easy reading on ebook reader


# About FLTK

The "Fast, Light Toolkit" (generally pronounced "fulltick") is a cross-platform GUI library, developed by Bill Spitzak and others. Made with 3D graphics programming in mind, it has an interface to OpenGL, but it is still suitable for general GUI programming.

Using its own widget, drawing and event systems (though FLTK2 has gained experimental support for optionally using the cairo graphics library) abstracted from the underlying system-dependent code, it allows for writing programs which look the same on all supported operating systems.

FLTK is free software, licensed under LGPL with an additional clause permitting static linking from applications with incompatible licenses. It includes FLUID (FLTK User Interface Designer), a graphical GUI designer that generates C++ source and header files.

In contrast to libraries like Qt and wxWidgets, FLTK uses a more lightweight design and restricts itself to GUI functionality. Because of this, the library is very small (the FLTK "Hello World" program is around 100 KiB), and is usually statically linked. It also avoids complicated macros and separate code preprocessors, and does not use the following advanced C++ features: templates, exceptions, RTTI or, for FLTK 1.x, namespaces. Combined with the modest size of the package, this leads to a relatively short learning curve for new users.

These advantages come with corresponding disadvantages. FLTK offers fewer widgets than most GUI toolkits and, because of its use of non-native widgets, does not have native look-and-feel on any platform.

