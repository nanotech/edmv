# edmv [![Build Status](https://travis-ci.org/nanotech/edmv.svg?branch=master)](https://travis-ci.org/nanotech/edmv)

Batch file renaming with your favourite `$EDITOR`.

    $ ls
    0601%20Introduction.mp4 
    0602%20Generic%20birthday%20attack.mp4 
    0603%20The%20Merkle-Damgard%20Paradigm.mp4 
    0604%20Constructing%20compression%20functions.mp4 
    $ edmv *
    qqxlr.]uu0jq3@q:wq
    $ ls
    6.1 Introduction.mp4
    6.2 Generic birthday attack.mp4
    6.3 The Merkle-Damgard Paradigm.mp4
    6.4 Constructing compression functions.mp4
