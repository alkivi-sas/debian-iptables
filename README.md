# Debian package to manage iptables

This contains all the files to build a debian package.
Looking for an already built package -> look into pkg directory

## Build

Install necessary package (see [Debian Doc](http://www.debian.org/doc/manuals/maint-guide/) for more info on necessary package)
```bash
git clone https://github.com/alkivi-sas/debian-iptables.git alkivi-iptables
cd alkivi-iptables
dpkg-buildpackage -rfakeroot -tc
http://www.debian.org/doc/manuals/maint-guide/
```

## Limitations

* This module has been tested on Debian Wheezy, Squeeze.

## License

All the code is freely distributable under the terms of the LGPLv3 license.

## Contact

Need help ? contact@alkivi.fr

## Support

Please log tickets and issues at our [Github](https://github.com/alkivi-sas/)
