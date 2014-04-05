node-on-the-pi
==============

Just a scratchpad repository for any node work I do on the raspberry pi

###cpp-integration-1

Taken directly from [here](http://www.benfarrell.com/2013/01/03/c-and-node-js-an-unholy-combination-but-oh-so-right/).
Prerequisites:

1. The node module gyp is used. This in turn requires gcc, python (**atleast 2.7**), make and build-essentials
2. Install gyp globally `npm install -g node-gyp`
3. Then, in the directory with the C/C++ and binding.gyp files, run `node-gyp configure build`
