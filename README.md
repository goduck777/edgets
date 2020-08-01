# edgets - Gentoo overlay

The main goal of edgets overlay is to bring you the newest versions of modern software available across the internet.

![edgets](https://user-images.githubusercontent.com/17854950/89108167-99178780-d436-11ea-9a0d-209319390f5b.png)

## Getting started

Edgets is available through layman, so all you need to do is install layman (if you don't have already) and add an overlay.

```
# emerge --ask app-portage/layman

# layman --sync-all
# layman --add edgets
```

More information about layman usage [here](https://wiki.gentoo.org/wiki/Layman#Usage).

## Unmasking packages

Most of the packages are masked, so you have to unmask them or tell portage to do so.

```
# emerge --ask <package-name> --autounmask   # type yes
# dispatch-conf                              # press u
```

More information about unmasking [here](https://wiki.gentoo.org/wiki/Knowledge_Base:Unmasking_a_package).

## Installing packages

Now, when overlay is added and package unmasked, you are ready to install it.

```
# emerge --ask <package-name>
```

## Featured packages

See [PACKAGES.md](https://github.com/BlueManCZ/edgets/blob/master/PACKAGES.md)

## Contribution

If you want to add, update or fix some package ebuild in edgets overlay,<br>
you can open new [issue](https://github.com/BlueManCZ/edgets/issues) or create a [pull request](https://github.com/BlueManCZ/edgets/pulls). Your contribution is welcome.
