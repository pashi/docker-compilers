# centos-7-compiler

development tools for centos7

Build docker
------------

docker build --rm -t ${USER}/centos-7-compiler .


Run docker
----------

docker run -h ${USER}-docker -v /your/source/tree/path/here:/work --rm -i -t pashi/centos-7-compiler


Build rpm on docker
-------------------

[build@pashi-docker rpmbuild]$ rpmbuild -bb SPECS/pmacct.spec
