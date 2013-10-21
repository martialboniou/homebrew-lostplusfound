Homebrew-lostplusfound
======================

How to install
--------------

Just type:

    brew tap martialboniou/lostplusfound

Then you can install any package with `brew install <formula>`.

If the formula conflicts with one from `mxcl/master` or another tap, you can force its installation:

    brew install martialboniou/lostplusfound/<formula>

Docs
----

`brew help`, `man brew`, or the Homebrew [wiki](https://github.com/mxcl/homebrew/wiki).

History
-------

Mountain Lion Xcode 5's Command Line Tool (`Xcode.CLTools.10.8-2013.9.2.dmg`) has no `cvs` (required by my [el-get](https://github.com/dimitri/el-get) install). By doing this, no more problem:

    brew tap martialboniou/lostplusfound && brew install cvs

The package `cvs` comes from [Bjørn Magnus Mathisen](https://github.com/epichub/homebrew-epicbrews/blob/master/cvs.rb).
