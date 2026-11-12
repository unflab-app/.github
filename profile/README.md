# [![unflab](https://unflab.app/assets/logotype.light.svg "unflab")](https://unflab.app)

Small, self-contained macOS command-line tools. One download each, no
package manager, and nothing installed that the tool doesn't actually
need.

```sh
curl -sL unflab.app/get | sh -s -- tree
```

That installs `tree` into `~/.local/bin`. Several at once works too:

```sh
curl -sL unflab.app/get | sh -s -- wget jq tree
```

Once you've installed one, it'll install a simple wrapper to reduce
that to:

```sh
unflab tree
```

And, if you're not a fan of running unknown scripts, all the packages
are available for download as `.tgz` files [on the _Releases_ page](https://github.com/unflab-app/unflab/releases)
that you can download and [install manually](https://unflab.app/#installing-manually).

No Homebrew. No Xcode. No runtime dependencies. All packages need to
work on a modern, freshly-installed Mac.
