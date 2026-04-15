# Atlas77 Raylib Bindings

This repository contains bindings for the Raylib library. The bindings have been generated using the `atlas77 package` command, and only a few QoL updates have been made (e.g.: some static functions added to `raylib::Color`). As it stands, we recommend to just fork the repository if you want to make a game or anything with it, as there is no way to import packages in Atlas77 yet. 

# Usage

Well, as for the usage, it's as close as it can be to the original Raylib library. You can find the documentation for the original library [here](https://www.raylib.com/), and the API reference [here](https://www.raylib.com/cheatsheet/cheatsheet.html).

# Contributing

If you want to contribute to the project, feel free to open a pull request or an issue. It's still very lacking and lack most of the QoL features. QoL features are, but not limited to:
- Adding more static functions to the structs (e.g.: `raylib::Color`, `raylib::Vector[2, 3, 4]`).
- Adding more helper functions (e.g.: `raylib::Color::from_hex`, `raylib::Color::to_hex`).
- Making some functions become methods for easier usage (e.g.: `raylib::Texture2D::draw`, `raylib::AudioStream::play`).