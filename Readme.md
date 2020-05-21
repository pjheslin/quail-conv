# Quail-conv

Emacs comes with a large number of input methods that allow the user conveniently to type text that can appear in your document as Unicode.  Many of these quail input methods correspond exactly to various 7-bit and 8-bit legacy encodings.  This package takes advantage of that correspondence to translate text in these encodings to utf-8.

My problem was that I had a large number of LaTeX files that used the old pre-Unicode Ibycus 7-bit encoding for polytonic (ancient) Greek.  I wanted to convert these to utf-8 when I switched to XeTeX, but the Ibycus encoding was too obscure the standard conversion utilities.  So I wrote this Emacs macro to do it.

The code here is supplied in case it may be of use to anyone who faces a similar challenge of converting an text encoding that is only supported as an Emacs input method.
