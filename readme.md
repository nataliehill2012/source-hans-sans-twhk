# Source Hans Sans / Noto Sans CJK with Traditional Chinese (TWHK) as the default 

A set of customized Multilingual OpenType/CFF files of Adobe's Source Hans Sans («ä·½¶ÂÅé) typeface [1], whic is also released by Google under the name of "Noto Sans CJK".

Several favors of the font has been released. The differences are documented at http://sourceforge.net/adobe/source-han-sans/wiki/Home/.

As said in the document, the Multilingual OpenType/CFF fonts **"represent the most compact form that supports all languages and includes the complete set of glyphs, but this comes at the expense of requiring the application to properly support the 'locl' GSUB feature in order to display in languages other than the default (Japanese)"**. One may choose to install the "Region-specific Subset OpenType/CFF" version, but the drawback is that the font only contains a subset of the glyphs.

This repository provides a modified version of the Multilingual OpenType/CFF fonts which changed the 'local' attribute to use Traditional Chinese as the default.

I followed the building instruction found at https://github.com/adobe-fonts/source-han-sans/issues/7.

[1] https://github.com/adobe-fonts/source-han-sans
[2] https://code.google.com/p/noto/source/browse/#git%2Fthird_party%2Fnoto_cjk
