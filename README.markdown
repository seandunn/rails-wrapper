Rails Wrapper
=============

Tiny little wrapper for the rails command to prevent the generation of
Rails projects called server and console every time I switch back to
Rails 2... :)

It checks the current Ruby to see if it's Ruby 1.8.7 and makes the
assumption that only old Rails 2 projects will still be using it so
converts the Rails 3 command into ./script/COMMAND
