Super Smartypants module documentation
Super Smartypants is a ProcessWire textformatter module which adds support for languages. It also allows you to set the different Smartypants Typographer parser attributes to customize which rules apply.

#Usage

After installation, add /site/modules/TextformatterSuperSmartypants/smartypants.php to your language translations.

To enable Super Smartypants for a language, set the Smartypants attributes field to 1, otherwise to disable leave the field empty.

#Smartypants Typographer parser available attribures 

leave empty : do nothing

1 : set all, except dash spacing

2 : set all, except dash spacing, using old school en- and em- dash shortcuts

3 : set all, except dash spacing, using inverted old school en and em- dash shortcuts

##Punctuation:

q -> quotes

b -> backtick quotes (\`\`double'' only)

B -> backtick quotes (\`\`double'' and \`single')

c -> comma quotes (,,double`` only)

g -> guillemets (\<\<double\>\> only)

d -> dashes

D -> old school dashes

i -> inverted old school dashes

e -> ellipses

w -> convert \&quot; entities to "

## Spacing:

: -> colon spacing +-

; -> semicolon spacing +-

m -> question and exclamation marks spacing +-

h -> em-dash spacing +-

H -> en-dash spacing +-

f -> french quote spacing +-

t -> thousand separator spacing -

u -> unit spacing +-

(you can add a plus sign after some of these options denoted by + to add the space when it is not already present, or you can add a minus sign to completly remove any space present)

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
