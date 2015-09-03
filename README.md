# github-clone

Written as an exercise to make me start using github

clones github-style repositories into directories named by user and
repo, e.g.

    /home/bob/projects$ github-clone https://github.com/sweth/github-clone.git

puts repo into

    /home/bob/projects/sweth/github-clone

If current dir matches github username from URL, then just creates
repo name, e.g.

    /home/bob/projects/sweth$ github-clone https://github.com/sweth/github-clone.git

ALSO puts repo into

    /home/bob/projects/sweth/github-clone

rather than

    /home/bob/projects/sweth/sweth/github-clone

TODO: Option to use 3-dir structure where PROTO://(STUFF.)*SITE.(SUFFIX)/PATH/TO/REPO clones into SITE/TO/REPO rather than TO/REPO.  Easy to do if I don't care about multi-level suffixes like .co.uk...
