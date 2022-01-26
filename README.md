# Zhixya

An experimental alternative leval format written in Rust for 2D indie games.

## Table of contents

* [Goals](#goals)
* [Installation](#installation)
* [Credits](#credits)

## Goals

Our goals are to implement a format simple to read and use, while providing access in both programatically and visually ways.
This table will be updated as we go evolving the library. Suggestions are welcome to add new features and improve existing ones.
* [ ] Find an efficient way to structure the level format itself
* [ ] Choose the right file format for the exported data (JSON, YAML, XML, RON, ...)
* [ ] Implement an efficient way to read and write the format
* [ ] Create an API to edit the data through I/O operations
* [ ] Entity positioning support
* [ ] Add serialization support to the API by using Serde
* [ ] Find an efficient way to implement the editor
* [ ] Make the editor cross-platform (Windows, Linux, MacOS, ...)

## Installation

There is no way to install or add Zhixya to your project in a stable way currently.

## Credits

* Our primary inspiration for structuring the library came from the [Leafwing Studios's template repository][template].

[template]: https://github.com/Leafwing-Studios/template-repo