<p align="center">
  <img src="https://raw.github.com/andrewmcv/raccoon/master/docs/images/rocket-logo.png" />
</p>
=======

Rocket is a foundation for experimenting with language constructs, expressiveness, dynamicity, and actor-based concurrency. We aim to do all this, as well as keeping performance on a par with natively compiled static languages.

It is based on luajit and a modified version of luma (a powerful hygienic macro system). It extends standard lua with language constructs for:

- actors & mapping to threads, with asynchronous support
- pattern matching, object decomposition
- a powerful class system based on composition, with full reflection
- list comprehensions and other data operations such as map
- exceptions

It is intended to be a language that can fully mature with a programmer's growing sophistication. It is 100% backwards compatible with Lua.

Our final aim is to keep the full distribution under 1.44mb, including all binaries and libraries and AJAX-based MVC system. Yep - the (uncompressed!) distribution should fit on a 3.5" floppy disk. We are not enforcing this because we actually care about old-school disk drives (!), but because of our belief that there is immense power in forcing ourselves to make tough choices about what to include in our system. We want to make a tiny, powerful language and environment (including IDE) that is "fully knowable".






