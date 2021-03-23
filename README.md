# Tigrosa Scripts

[Tigrosa Scripts](https://github.com/tiredpixel/tigrosa-x-bin) is an open-source (BSD 3-Clause) collection of scripts for [Tigrosa](https://docs.tigrosa.tiredpixel.com/#tigrosa) auth proxy. With these, it's possible to create organisations and users, login and create session tokens, and perform other operations using the Tigrosa API. These are useful not only in development, but also as a demo of Tigrosa's main capabilities, a quick way of performing actions even in production, and also in providing a functional reference for those wishing to develop their own programs on top of Tigrosa.

Also see the [Isoxya Scripts](https://github.com/isoxya/isoxya-x-bin), a collection of scripts for [Isoxya](https://www.isoxya.com/) web crawler, built on top of these scripts.


## Dependencies

- [jq](https://stedolan.github.io/jq/)


## Installation

These scripts are provided by way of example, but are also suitable for controlling the API via a CLI even in production. The repository can be cloned somewhere, and included in your PATH when required (or permanently in your `$HOME/.bash_profile`).

```sh
cd $HOME
git clone git@github.com:tiredpixel/tigrosa-x-bin.git

PATH=$PATH:$HOME/tigrosa-x-bin/bin
```


## Contact

[tp@tiredpixel.com](mailto:tp@tiredpixel.com) · [tiredpixel.com](https://www.tiredpixel.com/)

LinkedIn: [in/nic-williams](https://www.linkedin.com/in/nic-williams/) · GitHub: [tiredpixel](https://github.com/tiredpixel)


## Licence

Copyright © 2020-2021 [Nic Williams](https://www.tiredpixel.com/). It is free software, released under the BSD 3-Clause licence, and may be redistributed under the terms specified in `LICENSE`.
