filefrog/hugo Docker Image
=============================

Hugo is a static site generator that allows for some pretty DRY,
automatable website publishing pipelines, as a an alternative to
more heavy-handed CMSes like WordPress.  Here it is, in a Docker
image, so you don't have to install it to use it!

(provided that you have Docker available...)

To run it:

    docker run --rm -it filefrog/hugo [options]

This docker image is built such that any commands you pass it are
interpreted as arguments to the base `hugo` command.  In that
sense, `docker run ... filefrog/hugo` can be thought of as an
alias for the actual `hugo` command, except you don't have to
install the software, or its dependencies.

[1]: https://gohugo.io/
