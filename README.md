Atom Wrapper for Portable Apps
===================


Currently, there isn't a great way to run Atom as a portable package.  It leaves data on the host system and isn't great at storing it's data somewhere other than the default location.  This wrapper allows the Atom to be dropped in unaltered and run as a Portable App on the [PortableApps.com](http://portableapps.com/) Platform.



Instructions
-------------
After downloading the contents of this repository, your directory structure should look like this:

```
+-- AtomPortable
    +-- App
    |   +-- AppInfo
    |   |   +-- Launcher
    |   +-- Atom
    |   +-- DefaultData
    +-- Data
    +-- Other
        +-- Help
        |   +-- Images
        +-- Source
```

Simply download the latest stable zip release of [Atom](https://atom.io/) from the [Atom Gihub Repository](https://github.com/atom/atom/releases/) and unzip the files directly into the directory __AtomPortable\App\Atom__.

More information on creating PortableApps for the PortableApps.com platform can be found on the  [PortableApps.com Development Page](http://portableapps.com/development).
