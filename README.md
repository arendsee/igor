# Igor

This is a stub repo. I want to build a database of corpuses. A corpus may be
natural language (say Chinese newspapers) or code (say Haskell). Then I want to
be able to search a corpus for a given pattern. This is pretty simple stuff. Or
maybe flash through random files of name 'setup.py' to see how people generally
write them. Or get a list of the line 'Title' in the 'DESCRIPTION' file of 'R'
packages from the 'cran' database.

A corpus for a computer language needn't be terribly large. A thousand lines of
code only takes up around 50K. So if we find a few thousand github programs,
filtering based on number of stars (keeping programs that have, say, at least
5), and we assume an average program is 3000 lines, we end up with about
a gigabyte. The most trivial solution, would be to just download everything,
recursively delete the shit we don't want (.git/ etc), then just recursive grep
out the patterns we want. Of course, there is not limit to how sophisticated
this could get. We could build all the code into language-specific ASTs, then
search by grammars. We could build fantastic GUIs. Of course, we won't, because
we don't like such things. We like vim and emacs. This is why we don't make any
money. This is why we sit alone in dark places talking to ourselves in the
plural. This is why we crawl, like lizards, from the place underneath things,
shielding our eyes, looking, bewildered, looking at the eloi with their
fetchingly curled hair, their handbags and smiles -- all looking into their
glowing tablets -- we feel something is wrong, but it is hard to explain, so we
don't.

The name Igor is a Frankenstein reference to the fellow who goes to graveyards
looking for body parts. He mined corpses, we mine corpuses.
