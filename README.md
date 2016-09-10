[![GPLv2 License](http://img.shields.io/badge/license-GPLv3-brightgreen.svg)](https://tldrlegal.com/license/gnu-general-public-license-v3-(gpl-3))

# SDR# R820T Improved Plugin

This is a reconstruction of R820T Plugin for SDR#. This should be a in-place replace plugin fully compatible with the other `SDRSharp.R820T.dll` file.

# How to use it

Download the latest release here in github. It will include the necessary `SDRSharp.R820T.dll` and `librtlsdr.dll`

# How to compile it

Download Visual Studio 2016 (it works in Express) and set the reference path for `SDRSharp.Radio` in the solution `References`. You will also need our development release of librtlsdr (see https://github.com/librtlsdr/librtlsdr )

# TODO List

*   ~~Full reconstruction~~
*   ~~Bias T Support for RTLSDR V.3 Dongles~~
*   Bandwidth Selector


I hope you enjoy it!