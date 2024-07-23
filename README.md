# MapLibre Native Nix Flake

This Nix Flake may be helpful when setting up a development environment to build MapLibre Native.

At the time of writing for Linux builds only Ubuntu is officially supported and documented. Using Nix is more reproducible and cleaner and should work on any distro, but it is also still a bit niche and I may or may not keep this up to date, that is why I am sharing it here.

Nix installation instructions can be found here: https://zero-to-nix.com/start/install

Then you can run:

```
nix develop
```

to get a shell with all dependencies installed.