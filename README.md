# node.bcrypt.js

[bcryptwiki]: https://github.com/ncb000gt/node.bcrypt.js

+ 

[nan]: https://github.com/rvagg/nan

## Credits

The code for this comes from a few sources:

* blowfish.cc - OpenBSD
* bcrypt.cc - OpenBSD
* bcrypt::gen_salt - [gen_salt inclusion to bcrypt][bcryptgs]
* bcrypt_node.cc - me

## Contributors

* [Antonio Salazar Cardozo][shadowfiend] - Early MacOS X support (when we used libbsd)
* [Ben Glow][pixelglow] - Fixes for thread safety with async calls
* [Van Nguyen][thegoleffect] - Found a timing attack in the comparator
* [NewITFarmer][newitfarmer] - Initial Cygwin support
* [David Trejo][dtrejo] - packaging fixes
* [Alfred Westerveld][alfredwesterveld] - packaging fixes
* [Vincent Côté-Roy][vincentr] - Testing around concurrency issues
* [Lloyd Hilaiel][lloyd] - Documentation fixes
* [Roman Shtylman][shtylman] - Code refactoring, general rot reduction, compile options, better memory management with delete and new, and an upgrade to libuv over eio/ev.
* [Vadim Graboys][vadimg] - Code changes to support 0.5.5+
* [Ben Noordhuis][bnoordhuis] - Fixed a thread safety issue in nodejs that was perfectly mappable to this module.
* [Nate Rajlich][tootallnate] - Bindings and build process.
* [Sean McArthur][seanmonstar] - Windows Support
* [Fanie Oosthuysen][weareu] - Windows Support

## License
Unless stated elsewhere, file headers or otherwise, the license as stated in the LICENSE file.

[bcryptwiki]: http://en.wikipedia.org/wiki/Bcrypt
[bcryptgs]: http://mail-index.netbsd.org/tech-crypto/2002/05/24/msg000204.html
[codahale]: http://codahale.com/how-to-safely-store-a-password/
[gh13]: https://github.com/ncb000gt/node.bcrypt.js/issues/13
[jtr]: http://www.openwall.com/lists/oss-security/2011/06/20/2

[shadowfiend]:https://github.com/Shadowfiend
[thegoleffect]:https://github.com/thegoleffect
[pixelglow]:https://github.com/pixelglow
[dtrejo]:https://github.com/dtrejo
[alfredwesterveld]:https://github.com/alfredwesterveld
[newitfarmer]:https://github.com/newitfarmer
[zooko]:https://twitter.com/zooko
[vincentr]:https://twitter.com/vincentcr
[lloyd]:https://github.com/lloyd
[shtylman]:https://github.com/shtylman
[vadimg]:https://github.com/vadimg
[bnoordhuis]:https://github.com/bnoordhuis
[tootallnate]:https://github.com/tootallnate
[seanmonstar]:https://github.com/seanmonstar
[weareu]:https://github.com/weareu
