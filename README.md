# Prebuilt Qt

This project builds the official, unmodified, Qt source code for C++17 using
GitHub actions runners.


## Installation

Using `curl` to download and extract to `/opt/qt5`:

    curl -L https://github.com/constructpm/qt-build/releases/download/v5.15.8-lts-lgpl-1/boost-5.15.8-lts-lgpl-cpp17-$PLATFORM-x64.tar.gz | sudo tar -xJC /opt

where `$PLATFORM` is `ubuntu-18.04` or `ubuntu-22.04`.
