Gentoo Overlay for the Intel SGX
================

TODO

## Installing the Overlay

In order to [manage overlays](https://wiki.gentoo.org/wiki/Overlay), the
package [**app-portage/layman**](https://wiki.gentoo.org/wiki/Layman) must be
installed into your Gentoo environment:

```
emerge -av app-portage/layman
```

If the installation of _layman_ was successfully completed, then you are ready
to sync the content of this repository:

```
layman -o https://raw.githubusercontent.com/abusse/intel-sgx-overlay/master/master/repositories.xml -f -a intel-sgx
```

If you use [eix](https://wiki.gentoo.org/wiki/Eix) you may need to execute:

```
eix-update
```

TODO