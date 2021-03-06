# ![Valhalla](https://raw.githubusercontent.com/Bat41/valhalla/master/valhalla.png)

<p align="center">
  <a href="https://gitter.im/valhalla-chat/Lobby">
    <img align="center" alt="Gitter badge" src="https://img.shields.io/gitter/room/valhalla-chat/Lobby.svg?style=flat-square"/>
  </a>

  <a href="https://atom.io/packages/valhalla">
    <img align="center" alt="apm version" src="https://img.shields.io/apm/v/valhalla.svg?style=flat-square" />
  </a>

  <a href="https://atom.io/packages/valhalla">
    <img align="center" alt="apm downloads" src="https://img.shields.io/apm/dm/valhalla.svg?style=flat-square" />
  </a>
</p>

This package aims to turn Atom into a powerful Vala IDE. It provides you autocompletion as you write code. You can also access a local reference (with `valhalla:documentation`).

To make it work, you should first install the [language-vala-modern](https://atom.io/packages/language-vala-modern) package. It is also recommended to install [linter](https://atom.io/packages/linter) to see errors and warnings as you write code.

This package can eventually be combined with [builder](https://atom.io/packages/builder) and [tool-bar](https://atom.io/packages/tool-bar)

![Vala code autocompletion](https://raw.githubusercontent.com/Bat41/valhalla/master/autocomplete.png)

![Documentation](https://raw.githubusercontent.com/Bat41/valhalla/master/doc.png)

This package could slow down a little bit Atom's startup because it parses all the `.vapi` files you have installed on your system (around 200).

The icons are from [Valadoc.org](http://valadoc.org).

If you found a bug or have suggestion, please open an issue on GitHub.
