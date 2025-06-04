# libpango1.0-0

When you install bitscope sofware under Ubuntu:

```shell
sudo apt install ./bitscope-dso_2.8.FE22H_amd64.deb 
[sudo] password for xxxxx:
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
Some packages could not be installed. This may mean that you have
requested an impossible situation or if you are using the unstable
distribution that some required packages have not yet been created
or been moved out of Incoming.
The following information may help to resolve the situation:

The following packages have unmet dependencies.
 bitscope-dso : Depends: libpango1.0-0 (>= 1.14.0) but it is not installable
E: Unable to correct problems, you have held broken packages.
```

Because the dependency is now called libpango-1.0-0

## Usage

checkout this project

```shell
sudo apt install equivs
equivs-build libpango.equivs
sudo apt install ./libpango1.0-0_1.14.0_all.deb
```

Now you can install bitscope-*

