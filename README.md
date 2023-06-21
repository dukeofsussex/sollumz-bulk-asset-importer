# Sollumz Bulk Asset Importer

[![GitHub license](https://img.shields.io/github/license/dukeofsussex/gta-v-map)](https://github.com/dukeofsussex/sollumz-bulk-asset-importer/blob/master/LICENSE)

Script to help create a Blender asset library from GTA V assets.

## Prerequisites

* [Blender](https://www.blender.org/)
* [CodeWalker](https://github.com/dexyfex/CodeWalker)
* [Sollumz](https://github.com/Skylumz/Sollumz)

## Usage

1. Download this repo (as a ZIP using the green button above labelled "Code")
2. (Extract and) ```cd``` into the repository's folder
3. Prepare your [asset library](https://docs.blender.org/manual/en/latest/files/asset_libraries/introduction.html)
4. Export the assets you want to import as XML files via [CodeWalker](https://github.com/dexyfex/CodeWalker)
5. Configure the script by copying `config.example.py` to `config.py` and setting the provided parameters
6. Run the script using `<path to blender>\blender.exe -b -P import.py`

## Contributing

Any contributions made are welcome and greatly appreciated.

1. Fork the project
2. Create your feature branch (`git checkout -b feature`)
3. Code it
4. Commit your changes (`git commit -m 'Add something awesome'`)
5. Push to the branch (`git push origin feature`)
6. Open a Pull Request

## License

This project is licensed under the GNU GPL License. See the [LICENSE](LICENSE) file for details.
