# Scratux 
Scratux is a block-based visual programming language targeted primarily at children. Users can create projects using a block-like interface. With Scratux, you can program your own interactive stories, games, and animations — and share your creations with others in the online community.

Basically Scratux is a simple project that aims to provide Free/Libre Open Source Linux binaries of Scratch Desktop. Since the official Scratch project does not provide binaries for Linux distributions, we created this project so you do not have to download + build from source. Just click and install it.

Scratux is built-in different languages and is always based on the latest stable Scratch Desktop release. Currently it is fetching Scratch Desktop 3.29.1

![Screenshot](https://dashboard.snapcraft.io/site_media/appmedia/2020/03/window_OLzR3hd.png)

Download/Install
----
[Download latest release from the official page](https://scratux-revived.github.io/#download)

Screenshots
----
### Ubuntu
![Ubuntu](https://dashboard.snapcraft.io/site_media/appmedia/2020/05/scratux_ubuntu_2004_RPhn0Ev.png)

### Manjaro
![Manjaro](https://dashboard.snapcraft.io/site_media/appmedia/2020/05/scratux_manjaro_SfK6wYb.png)

### Fedora
![Fedora](https://dashboard.snapcraft.io/site_media/appmedia/2020/05/fedora_scratux_dSrC33b.png)

Development
----
First, download this branch and run the `fetch.sh` script. This will donwload our latest `scratux-desktop`, `scratux-gui` and `scratux-i18n` repositories and will initialize them.

```sh
$ git clone https://github.com/scratux/scratux.git
$ cd scratux
$ chmod +x fetch.sh
$ ./fetch.sh 
```
 
 Then you can run Scratux using `yarn` or `npm`:

```sh
$ cd src
$ npm start
```
or build it by:

```sh
./build.sh
```
[More info in the wiki](https://github.com/scratux-revived/scratux/wiki/Development)

Get Involved
----
* Test, report bugs and request new features. 

License
----
Licensed under BSD-3-Clause
