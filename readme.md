# Source Han Sans / Noto Sans CJK that defaults to Traditional Chinese (TWHK) 

A set of customized Multilingual OpenType/CFF files of Adobe's Source Han Sans (思源黑體) typeface [1], also released by Google with a different name "Noto Sans CJK".

There are several favors of the typeface, and their differences are well documented at http://sourceforge.net/adobe/source-han-sans/wiki/Home/.

As said in the document, the Multilingual OpenType/CFF fonts *"represent the most compact form that supports all languages and includes the complete set of glyphs, but this comes at the expense of requiring the application to properly support the 'locl' GSUB feature in order to display in languages other than the default (Japanese)"*. One may choose to install the "Region-specific Subset OpenType/CFF" version, but the drawback is that the font only contains a subset of the glyphs.

This repository provides a modified version of the Multilingual OpenType/CFF fonts which uses Traditional Chinese glyphs as the default.

I followed the building instruction found at https://github.com/adobe-fonts/source-han-sans/issues/7.

[1] https://github.com/adobe-fonts/source-han-sans

[2] https://code.google.com/p/noto/source/browse/#git%2Fthird_party%2Fnoto_cjk
