# Docker Python Image

This repository contains the script to pull the python 2.7, 3.8 and 3.11 slim images as tar files into Delphix engines.
The location to save the images is `debian/tmp/var/lib/delphix-virtualization` and in Delphix engine it is saved at
`/var/lib/delphix-virtualization`.

## Contributing

To add a new image, update the [rules](/debian/rules) file with the Python Slim image and version. The image should be
present at `registry.delphix.com`.

## License

This project is licensed under the Apache 2.0 License - see the [LICENSE](LICENSE) file for details.