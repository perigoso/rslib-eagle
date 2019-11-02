# RSLib

My preferred component footprints using Eagle.
Please note that I guarantee that there are some messed up and untested footprints in this library. 
By downloading these files, you acknowledge that you are using the files at your own risk. 

**I cannot be held responsible for faulty PCBs.**

## Library Descriptions

I grouped the various parts into individual libraries and folders to make it as easy as possible to locate the part I need:

TODO:

* **lbr name** - description 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

obviously.

```
EAGLE CAD 
```

### Installing

A step by step series of examples that tell you how to get a development env running

There are two ways to setup this "library"

#### 1. Overwrite:

clone the repository next to EAGLE directory (the default location for user libraries and etc.)

```
cd ~
git clone https://github.com/gimbas/rslib
```

copy anything you want to keep to the rslib equivalent folder

delete the original EAGLE directory

```
rm -rf EAGLE/
```

rename rslib to EAGLE

```
mv rslib EAGLE
```

done.

#### 2. Complementary:

clone the repository to your desired location

```
git clone https://github.com/gimbas/rslib
```

add the desired rslib diretories from within EAGLE

```
from eagle 'Control Pane'
Options > Directories...
select directory path textbox and then Press 'Browse...'
search the rslib directory and add it
```

done.

## Contributing

Currently not looking for external contributers.

Please read [CONTRIBUTING.md](//) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Rafael Silva** - *initial work* - [gimbas](https://github.com/crying-face-emoji)

See also the list of [contributors](https://github.com/gimbas/rslib/graphs/contributors) who participated in this project.

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE.md](LICENSE.md) file for details
**You are welcome to use this library for commercial purposes.**

Please consider contributing back to this library or others to help the open-source hardware community continue to thrive and grow! 

## Acknowledgments

* **vankxr** - *some footprints were imported from his library* - [eagle-cfg](https://github.com/vankxr/eagle-cfg)