Python version
CircleCI uses pyenv to manage Python versions. Here’s an example of how to set the version of Python used for your tests.

machine:
  python:
    version: 2.7.5
You can find more details about pre-installed versions for Ubuntu 14.04 (default) and Ubuntu 12.04.

GHC version
machine:
  ghc:
  version: 7.8.3
You can find more details about supported versions here.

Other languages
We also support other languages including Clojure, C/C++, Golang, and Erlang.

Pre-installed versions are different depending on which build image you are using.

Please check out Ubuntu 12.04 build image and Ubuntu 14.04 build image to find out what versions are supported.

