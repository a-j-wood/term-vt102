Project has left GitHub
-----------------------

It is now here: [https://codeberg.org/a-j-wood/term-vt102](https://codeberg.org/a-j-wood/term-vt102)

This project was briefly hosted on GitHub.  GitHub is a proprietary,
trade-secret system that is not Free and Open Source Software (FOSS).

Read about the [Give up GitHub](https://GiveUpGitHub.org) campaign from
[the Software Freedom Conservancy](https://sfconservancy.org) to understand
some of the reasons why GitHub is not a good place to host FOSS projects.

Any use of this project's code by GitHub Copilot, past or present, is done
without permission.  The project owner does not consent to GitHub's use of
this project's code in Copilot.

![Logo of the GiveUpGitHub campaign](https://sfconservancy.org/img/GiveUpGitHub.png)


README
------

This is the README file for Term::VT102, a Perl module which provides
emulation of a VT102 terminal.

Like the "expect" Tcl extension, this module is intended primarily for use
as a way of automating processes; for instance, you can write a script which
connects via telnet to a full-screen service of some kind (such as a router,
or a telephone switch), uses this module to parse the output, and therefore
can tell what is currently "on the screen" and react accordingly.  "Expect"
cannot really do this, as it is stream-oriented, rather than being able to
tell you, say, what's on the top row of the screen.

For installation instructions, see the INSTALL file.

Please send bug reports, comments, and whatnot to the project maintainer,
Andrew Wood (andrew dot wood at ivarch dot com).

Credit is also due to:

 * Charles Harker (CHarker at interland dot com) - reported and helped to diagnose a bug in the handling of TABs
 * Steve van der Burg (steve dot vanderburg at lhsc dot on dot ca) - supplied basis for an example script using Net::Telnet
 * Chris R. Donnelly (cdonnelly at digitalmotorworks dot com) - added support for DECTCEM, partial support for SM/RM
 * Paul L. Stoddard - reported a possible bug in cursor movement handling
 * Joerg Walter - provided a patch for Unicode handling
 * "hughhome" - fixed row ordering bug in usage examples

