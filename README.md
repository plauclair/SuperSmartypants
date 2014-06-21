Super Smartypants module documentation
Super Smartypants is a ProcessWire textformatter module which adds support for languages. It also allows you to set the different Smartypants Typographer parser attributes to customize which rules apply.

#Usage

After installation, add /site/modules/TextformatterSuperSmartypants/smartypants.php to your language translations.

To enable Super Smartypants for a language, set the Smartypants attributes field to 1, otherwise to disable leave the field empty.

#Smartypants Typographer parser available attributes 

leave empty : do nothing

1 &#8658; set all, except dash spacing

2 &#8658; except dash spacing, using old school en- and em- dash shortcuts

3 &#8658; except dash spacing, using inverted old school en and em- dash shortcuts

##Punctuation:

q &#8658; quotes

b &#8658; backtick quotes (\`\`double'' only)

B &#8658; backtick quotes (\`\`double'' and \`single')

c &#8658; comma quotes (,,double`` only)

g &#8658; guillemets (\<\<double\>\> only)

d &#8658; dashes

D &#8658; old school dashes

i &#8658; inverted old school dashes

e &#8658; ellipses

## Spacing:

You can add a plus sign after some of these options denoted by + to add the space when it is not already present, or you can add a minus sign to completly remove any space present. All of those are disabled by default. For example, use :+ to add spacing before colons, and inversely :- to remove them.

: &#8658; colon spacing (optional additional + or -)

; &#8658; semicolon spacing (optional additional + or -)

m &#8658; question and exclamation marks spacing (optional additional + or -)

h &#8658; em-dash spacing (optional additional + or -)

H &#8658; en-dash spacing (optional additional + or -)

f &#8658; french quote spacing (optional additional + or -)

t &#8658; thousand separator spacing (optional additional -

u &#8658; unit spacing (optional additional + or -)

**License**

The MIT License (MIT)

Copyright (c) 2014 Pierre-Luc Auclair

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
