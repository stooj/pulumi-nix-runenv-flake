# pulumi-nix-runenv-flake

**WARNING: DO NOT USE THIS**

It is impure, and expects you to have pulumi binaries installed in a local
directory rather than pulling them from nixpkgs. It works for me, but it sucks
for everyone else.

I'll fix it some day.

[Nix Flake](https://nixos.wiki/wiki/Flakes) packaging of tools used for using
[Pulumi](https://github.com/pulumi/pulumi).

```
$ nix develop  # enters sub-shell with all the pulumi dependencies in PATH
$ pulumi version
v3.93.0
```

**DID YOU SEE THE WARNING AT THE TOP?**
