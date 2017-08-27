#Theme for [SLiM](http://slim.berlios.de/) with [NixOS](http://nixos.org/) thematics.
![preview](https://github.com/jpotier/nixos-slim-theme/raw/master/preview.png)

## How to use

To use this slim theme in NixOS you set the `theme` option, like so:

```
  slim = {
    enable = true;
    theme = pkgs.fetchurl {
      url    = "https://github.com/jpotier/nixos-slim-theme/archive/green.tar.gz";
      sha256 = "12srvdczgagikzsh2im6941m6spixa7nh0wsfpf0rfaq76zjmy76";
    };
  };
```

Then you need to do `nixos-rebuild switch` and restart slim to apply the theme.
