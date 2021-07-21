# PharUtil fork

[The original PharUtil repo](https://github.com/koto/phar-util) hasn't received updates since 2012. The code still works, but it can no longer be installed from the author's PEAR channel.

This fork contains updated instructions on how to build and install this package.

## Installation instructions

First, [clone this repository](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository) or [download the latest version as a zip file](https://github.com/GabrielMajeri/phar-util/archive/refs/heads/master.zip).

For building the package you will need to install a recent verison of PHP and [the PEAR command line tools](https://pear.php.net/manual/en/installation.getting.php)

Open a terminal in this folder and build the package using the following command:

```sh
pear package
```

This will generate a `PharUtil-0.6.1.tgz` file.

Install it by running:

```sh
pear install PharUtil-0.6.1.tgz
```

(you might have to prefix the command with `sudo` on Linux)

## License

The modifications made in this fork are licensed under [the MIT license](LICENSE), just like the original code.
