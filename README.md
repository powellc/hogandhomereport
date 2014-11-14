The Hog and Home Report
=======================


Easy bootstrapping!
-------------------

Powered by the ubiquitous Makefile ... this should be pretty easy:

1. make install
2. make run
3. open your browser to: http://127.0.0.1:45000


Librarys, librarys, librarys!
-----------------------------

Of course, we could provide a vagrant file and a provisoner and all 
that jazz. But I'd rather provide a make file for installing everything
into a venv and let you muck about with libraries. Those of you on
Linux shouldn't have too much trouble installing the requisite development
libraries below. The names are for debian-based distros, but they 
exist for all major distros. 

On Mac it may be a little tricker. Homebrew will get you quite far, but
first you have to install the bloated XCode and the CLI tools.

The libraries are:

  * libmemcached-dev
  * libfreetype6-dev
  * libjpeg-dev

Basics
------

This repository provides a very basic news budget management scheme.

Effectively, you set up your paper, invite collaborators, finalize
publications, solicit photos, and put it all together.

The whole thing is a farce, but it's a farce built around honest family facts.
Rather than dryly noting that your daughter is now living in Rwanda, why not
make a mock interview where you prompt her to answer quesitons completely
unrelated to Africa?

Fake ads are a big part of this too. We should have ad placements and requests
can go out for ads of a certain size and they rotate.

For a layout, I'm thinking something almost like Google+ where we have a lot of
little windows into content, with hilarious headlines and previews of the
content beneath.
