# Qt5-arm-cross-build
Docker scripts for building a qt5 opensource image via cross-compilation

In progress. Based on [this post](https://www.docker.com/blog/compiling-qt-with-docker-multi-stage-and-multi-platform/).

Please note that while these scripts are [unlicensed](https://github.com/polesapart/Qt5-arm-cross-build/blob/main/LICENSE), 
the QT source and the built binaries are subject to QT's licensing policy
(which sucks, IMHO, but [IANAL](https://en.wikipedia.org/wiki/IANAL)).

This is currently a starting point. I plan to make it generate instead of binaries
that runs on the host, a docker image which has the full sdk in.
