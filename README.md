## Packaging

 fpm --log error --after-install install.sh --after-remove  uninstall.sh --architecture armhf --name kintarosnes --version x.x.x -s dir -t deb --vendor Michael --description "Kintaro SNES PCB Driver"  -d python-rpi.gpio -d python3-dialog -d python3-rpi.gpio .

 
## Authors

* **Michael Kirsch** - *Initial work*

See also the list of [contributors](https://github.com/michaelkirsch/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

