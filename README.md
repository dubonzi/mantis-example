# Mantis Examples

This repository contains an example of how to run Mantis with a few mappings containing the different ways of matching that Mantis supports.

To run it, simply run `docker run --rm -p8090:8090 -p8091:8091 $(docker build -t mantis-example -q .)` in the terminal.

Check the `mappings` folder and make requests to port `8090` to try and match with the mapping definitions.

For more info, read the [documentation](https://dubonzi.github.io/mantis) and check out the [main repository](https://github.com/dubonzi/mantis).