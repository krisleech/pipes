# PIPES

## Install

Create a pipe:

    $ mkfifo runner

## Usage

    $ ./listen
    $ ./say

`listen` will wait for and execute messages on the `runner` pipe until terminated.
`say` sends a message `ls -al` to the `runner` pipe.
