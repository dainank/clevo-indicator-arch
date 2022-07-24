Clevo Fan Control Indicator for Arch
======================================

This program is an Arch indicator to control the fan of Clevo laptops, using reversed-engineered port information from ECView.

It shows the CPU temperature on the left and the GPU temperature on the right, as well as a menu for manual control.

For command-line, use *-h* to display help, or a number representing the percentage of fan duty to control the fan.


Build and Install
-----------------

```shell
sudo apt-get install libappindicator3-dev libgtk-3-dev
git clone https://github.com/dainank/clevo-indicator-arch.git
cd clevo-indicator-arch
make install
```

Additional Notes
-----
See original README: https://github.com/SkyLandTW/clevo-indicator/blob/master/README.md

