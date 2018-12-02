# awesome-vala [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

 A not-much-curated list of awesome Vala libraries.

## Contents

- [Code analysis](#code-analysis)
- [Compilers](#compilers)
- [Crypto & Security](#crypto--security)
- [Data Structures & Data Types](#data-structures--data-types)
- [Games](#games)
- [Graphic Libraries](#graphic-libraries)
- [GUI Programming](#gui-programming)
- [Language servers](#language-servers)
- [Logging](#logging)
- [Multimedia Processing](#multimedia-processing)
- [Numerical Computation](#numerical-computation)
- [ORM](#ORM)
- [Package and dependency management](#package-and-dependency-management)
- [Project samples and scaffolds](#project-samples)
- [Stacktrace](#stacktrace)
- [Templating](#templating)
- [Language integrations](#language-integration)
- [Tutorial](#tutorial)
- [Unit testing](#unit-testing)
- [Web Development](#web-development)
- [XML & Data Serialization](#xml--data-serialization)
- [Others](#others)

https://github.com/naaando/console-command

## Code analysis

- [Vala-Lint](https://github.com/elementary/vala-lint) - Small command line tool and library for checking Vala code files for code-style errors. Based on the elementary Code-Style guidelines.

## Compilers

- [Maja](https://github.com/lethalman/maja) - Vala to Javascript compiler.
- [ValaSharp](https://github.com/smx-smx/ValaSharp) - The Vala Compiler, ported to C#.
- [vlang: LLVM compiler for Vala](https://github.com/termNinja/vlang) - LLVM based compiler for Vala programming language.

## Crypto & Security

- [GnuTLS](https://www.gnutls.org/) - A secure communications library implementing the SSL, TLS and DTLS protocols and technologies around them. It provides a simple API to access the secure communications protocols as well as APIs to parse and write X.509, PKCS #12, and other required structures.

## Data Structures & Data Types

- [Libgee](https://wiki.gnome.org/Projects/Libgee) - A utility library providing GObject-based interfaces and classes for commonly used data structures (lists, maps, queues, trees, etc.).
- [Graphene](https://github.com/ebassi/graphene) - A thin layer of types for graphic libraries. It provides common types needed to handle 3D transformations: points, triangles, rectangles, quads, quaternions, vectors, matrices, spheres, etc.
- [Numeric-GLib](https://github.com/arteymix/numeric-glib) - A collection of numeric data types for GLib (and Vala) via GCC extensions. It includes 128 bit integers & floats, complex types, vectorized operations, and decimal types.

## Games

- [Asteroids_Vala](https://github.com/august0815/Asteroids_Vala) - A game testing darkcore lib with 4 gaming levels.

## Graphic Libraries

- [Cairo](https://cairographics.org/) - A 2D graphics library with support for multiple output devices. This is pretty much the default library you get in Vala.
- [SDL2](https://www.libsdl.org/) - A cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL, Direct3D, and Vulkan. Community bindings are available [here](https://github.com/sdl2-vapi/sdl2-vapi).
- [GRX](https://github.com/ev3dev/grx) - A graphics library for simple graphics displays (think 1-bit displays or Adafruit's PiTFT displays). It also includes keyboard, mouse, joystick and touchscreen input support.
- [GEGL](http://gegl.org/) - A data flow based image processing framework, providing floating point processing and non-destructive image processing capabilities. Think of it as "Reactive Programming for Images".
- [Babl](http://gegl.org/babl/) - A dynamic, any to any, pixel format translation library.

## GUI Programming

- [GTK+](https://www.gtk.org/) - The de facto library fro GUI development in Vala. Bindings are included with the vala compiler.
- [Granite](https://github.com/elementary/granite) - Granite is a companion library for GTK+ and GLib. Among other things, it provides complex widgets and convenience functions designed for use in apps built for elementary OS.
- [libgtkcanvas](https://github.com/Philip-Scott/libgtkcanvas) - This is the shared canvas specially built for Akira and Spice-Up. It will be written in Vala and use clutter for the drawing. It is meant to contain the basic elements such as a basic container class, move, resize and rotate. As well as the ability to have custom shapes and be able to drag each of their individual points.
- [Circular Progress Bar](https://github.com/phastmike/vala-circular-progress-bar) - A Circular progress bar Gtk.Widget.

## Language integrations
- [mkjni](https://github.com/DasJott/mkjni) - Write some functionality in Vala, specify a class you want to "export" to Java and mkjni creates a jni lib and the Java Class for you. So it feels like you could call the Vala class from Java!
- [Great Vala jscore](https://github.com/diorahman/greet-vala-jscore) - Send a JavaScript object from JavaScript within an instance of WebView and expect callback message from vala.

## Language servers

- [Vala Language Server](https://github.com/benwaffle/vala-language-server) - code intelligence for vala
- [vala-code](https://github.com/thiagoabreu/vala-code) - Vala language support for Visual Studio Code.
- [GNOME Vala Language Server](https://gitlab.gnome.org/esodan/gvls) - GNOME Vala Language Server is a library designed to provide services for IDEs using Vala as programming language.

## Logging
- [Log4Vala](https://github.com/nmelnick/Log4Vala) - A logging provider for Vala/GObject applications, similar to log4j and log4net.

## Multimedia Processing

- [GStreamer](http://gstreamer.freedesktop.org/) - A powerful framework for creating multimedia applications.

## Numerical Computation

- [vast](https://github.com/rainwoodman/vast) - A project for generative modelling in Vala. Think of TensorFlow rewritten in Vala.

## ORM

- [Almanna ORM](https://github.com/AmbitionFramework/almanna) - The Almanna ORM for Vala/GLib.

## Package and dependency management

- [Drakkar](https://github.com/valum-framework/drakkar) -  Package manager's specifications for Vala.
- [Vanat](https://github.com/vanat/vanat) - Dependency Manager for Vala.

## Project samples and scaffolds
- [generator-vala](https://github.com/eddiemoore/generator-vala) - Vala app generator for Elementary OS
- [plugin-app] (https://github.com/voldyman/plugin-app)- Sample app to show how to use libpeas for plugins in vala
- [Vala Gtk3 Tutorial](https://github.com/abenga/valagtk3tutorial) - GTK+ Programming Using The Vala Programming Language
- [vala-starter](https://github.com/benwaffle/vala-starter) - This is a starter template for Vala applications, that comes with meson set up. It also features composite templates.
- [Archetype](https://github.com/kjlaw89/archetype) - Create new Vala projects with ease.
- [AUTOVALA](https://gitlab.com/rastersoft/autovala) - A program that automatically generates CMake and Meson configuration files for your Vala project.
- [app-template](https://github.com/elementary/app-template) - Example template for an elementary OS app. Designed to be an example for AppCenter Dashboard and a starting point for your very own app.
- [Apollo11](https://github.com/Nine-H/apollo11) - The goal is to develop a skeleton to save developers starting from tabula rasa for every new project and allow them to expect to be able to publish from T minus zero.
- [Sampala](https://github.com/tadeboro/Sampala) - Small sample application, developed in Vala, to learn about Autotools and i18n.
- [gnome-builder-vala-granite-boilerplate](https://github.com/roymckenzie/gnome-builder-vala-granite-boilerplate) - A Vala, Granite boilerplate for GNOME Builder.

## Stacktrace

- [Vala Stacktrace](https://github.com/PerfectCarl/vala-stacktrace) - A class to display stacktrace within your vala application.
- [ivy](https://github.com/I-hate-farms/ivy) - Displays your vala stacktraces (on crashes, critical warnings and on invocation).

## Templating

- [Compose](https://github.com/arteymix/compose) - A functional templating library for Vala.
- [template-glib](https://gitlab.gnome.org/GNOME/template-glib) - A library for template expansion which supports calling into GObject Introspection from templates.

## Tutorial
- [Adaptation of Design Pattern for Humans to Vala](https://github.com/phastmike/vala-design-patterns-for-humans) - A Vala version of "Design Patterns for Humans" [Design patterns for humans/Vala](https://github.com/design-patterns-for-humans/vala).
- [Vala tutorial - ebook version](https://github.com/samvasko/vala-tutorial-book) - Epub/Mobi version of Vala tutorial https://wiki.gnome.org/Projects/Vala/Tutorial
- [The vala guide](https://github.com/vamega/The-Vala-Guide) - A book that teaches Vala.

## Unit testing
- [valadate](https://github.com/astavale/valadate) - Unit Testing framework based on GLib Test.

## Web Development

- [Valum](https://github.com/valum-framework/valum) - A Web micro-framework entirely written in Vala.
- [Ambition](https://github.com/AmbitionFramework/ambition) - A web framework written in Vala, with the MVC pattern in mind. Kinda unmaintained (someone could refactor it to use Valum under the hood, and maybe move it to Meson 😉).
- [Pawalicious](https://github.com/joseph-montanez/Pawalicious) - Pawalicious is proof of concept that web development can be done in Vala. It is heavily reliant on libsoup for serving generated content.
- [VServer](https://github.com/bcedu/ValaSimpleHTTPServer) - Simple HTTP server made in vala, VServer is "inspired" in the well known python SimpleHTTPServer.
- [Vala Server Gateway Interface (RFC)](https://github.com/antono/vsgi) - Unified Web Server Interface for Vala.

## XML & Data Serialization

- [GXML](https://gitlab.gnome.org/GNOME/gxml/) - A GObject API for manipulating XML and a Serializable framework from GObject to XML.
- [Json-GLib](https://gitlab.gnome.org/GNOME/json-glib/) - Implements a full JSON parser and generator using GLib and GObject, and integrates JSON with GLib data types.
- [libyaml-glib](https://github.com/rainwoodman/libyaml-glib) - The GLib binding of libyaml, plus a GObject builder that understands YAML.
- [EasyJSON](https://github.com/unyieldinggrace/EasyJSON) - Syntactic sugar to JSON-Glib. It's mainly meant for making it easy to generate JSON documents for sending to single-page web applications.

## Others

- [valadoc](https://github.com/Valadoc/valadoc-org) - Build-tools used to generate valadoc.org.
- [Valder](http://activey.github.io/valder/) - Valder the Vala code welder is intended to be a general purpose build tool dedicated for Vala language based projects. We try to keep Valder as simple and intuitive as possible mantaining it's elastic and quite powerful design. Valder is loosely inspired by Maven build tool for Java using only it's general idea of plugins based architecture.
- [TensorFlow for Vala](https://github.com/arrufat/tensorflow-vala) - Vala bindings for TensorFlow.
- [Extra VAPIs](https://github.com/nemequ/vala-extra-vapis) - Provides Vala bindings to various libraries which do not provide their own bindings, and for which valac does not provide bindings.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Mario Daniel Ruiz Saavedra and the other contributors have waived all copyright and
related or neighboring rights to this work.
