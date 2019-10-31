Try it here: https://topaz.github.io/paste/

This is a no-datastore, client-side paste service.  It turns text into [LZMA](https://en.wikipedia.org/wiki/Lempel%E2%80%93Ziv%E2%80%93Markov_chain_algorithm)-compressed, [Base64](https://en.wikipedia.org/wiki/Base64)-encoded URLs.

Because the entire paste is inside the URL, there's no risk of losing your data because a 3rd-party service vanished or deleted old pastes.  If you have the URL, you have the pasted data.

Uses [LZMA-JS](https://github.com/LZMA-JS/LZMA-JS) (© 2016 Nathan Rugg <nmrugg@gmail.com>).
