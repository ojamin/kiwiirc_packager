# kiwiirc_packager
Builds Kiwi IRC packages for distribution

What it does:

1. Clones and builds `https://github.com/kiwiirc/kiwiirc.git`
2. Clones ands compiles `https://github.com/kiwiirc/webircgateway.git` for multiple OSs
3. Merges the two projects together and adds default configuration files to get it running as easy as possible
4. Zips each package up into the packaged/ folder