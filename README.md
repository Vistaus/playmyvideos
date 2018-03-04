<div>
  <h1 align="center">Cinema</h1>
  <h3 align="center"><img src="data/icons/com.github.artemanufrij.playmyvideos.svg"/><br>A video player for watching local video files</h3>
  <p align="center">Designed for <a href="https://elementary.io"> elementary OS</p>
</div>

### Donate
<a href="https://www.paypal.me/ArtemAnufrij">PayPal</a> | <a href="https://liberapay.com/Artem/donate">LiberaPay</a> | <a href="https://www.patreon.com/ArtemAnufrij">Patreon</a>

<p align="center">
  <a href="https://appcenter.elementary.io/com.github.artemanufrij.playmyvideos">
    <img src="https://appcenter.elementary.io/badge.svg" alt="Get it on AppCenter">
  </a>
</p>
<p align="center">
  <img src="screenshots/Screenshot.png"/>
  <br/>
  <img src="screenshots/Screenshot_Player.png"/>
</p>

## Install from Github.

As first you need elementary SDK
```
sudo apt install elementary-sdk
```
Install dependencies
```
sudo apt install cmake
sudo apt install cmake-elementary
sudo apt install debhelper
sudo apt install libgranite-dev
sudo apt install libsqlite3-dev
sodo apt install libsoup2.4-dev
sudo apt install libgstreamer-plugins-base1.0-dev
sudo apt install libclutter-gtk-1.0-dev
sudo apt install libclutter-gst-3.0-dev
sudo apt install valac
```
Clone repository and change directory
```
git clone https://github.com/artemanufrij/playmyvideos.git
cd playmyvideos
```

Create **build** folder and compile application
```
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX=/usr ..
make
```

Install and start Play My Videos on your system
```
sudo make install
com.github.artemanufrij.playmyvideos
```
