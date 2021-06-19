# updeit

[![License: MIT](https://img.shields.io/github/license/un0tec/updeit?color=orange)](LICENSE)
[![Release](https://img.shields.io/github/v/release/un0tec/updeit?color=green&label=Release)](https://github.com/un0tec/updeit/releases/latest)


## README Content
1. :notebook_with_decorative_cover: [Description](#-description)
2. :warning: [Before running](#-before-running)
3. :writing_hand: [Syntax](#-syntax)
4. :bookmark_tabs: [Options](#-options)
5. :monocle_face: [Preview](#-preview)
6. :page_with_curl: [License](#-license)
7. :heart: [Contribution](#-contribution)

## # Description

Bash script to update Debian-based | Ubuntu | Linux | Raspberry systems.

## # Installation

Download and place the script in the desired path. Then assign execute permissions to the script with the following command:

    sudo chmod +x ./updeit

If you want to  run the script from anywhere on the system, place the file in `/usr/local/bin` directory or add the folder where it is to the `$PATH` system variable.

## # Syntax

    updeit [OPTIONS]

## # Usage

Run the following command to start the update:

     sudo ./updeit

You can see default values in [options](#-options) section

_Its recommended to run the command with_ `sudo`

## # Options

You can use the following options:

    -rpi            update raspberry system. Note that user interaction may be required using this option

    -v|--verbose    verbose mode

    -h|--help       show help page

    --version       print script version and exit

## # Preview

Here you can see an example of script execution:

![Preview](images/run_output.png)

## # License

Distributed under the MIT License. See `LICENSE` for more information.

## # Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

:star: Feel free to contribute :star:
