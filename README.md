[![](./ten-years-challenge.png)](./ten-years-challenge.pdf)

# Ten Years Reproducibility Challenge

Did you ever try to run an old code that you wrote for a scientific article you
published years ago? Did you encounter any problems? Were you successful?
We are curious to hear your story. This is the reason why we are
editing a special issue of ReScience to collect these stories.

The ten years reproducibility challenge is an invitation for researchers to try
to run the code they've created for a scientific publication that was published
more than **ten years ago**. This code can be anything (statistical analysis,
numerical simulation, data processing, etc.), can be written in any language
and can address any scientific domain. The only mandatory condition to enter
the challenge is to have published a scientific article **before 2010**, in a
journal or a conference with proceedings, which contains results produced by
code, irrespectively of whether this code was published in some form at the
time or not.

Note that we do not ask you to write a new version of your old code. We ask you
instead to **try to make your old code to run on modern hardware/software**
(with minimal modifications) in order to check if you can obtain the exact same
results that were publised at least ten years ago.

Sounds easy? We have good reasons to think this might be more difficult than you
think. And maybe the first problem you'll have to solve is to find your own source
code (see the [resources](#resources) section for help).

### Important dates

The challenge will run for a few months, until **April 1st, 2020** (because
we'll need time to review the different submissions). We'll organize a workshop
in Bordeaux (France) sometime in **June 2020** (date not yet settled) to
present the results. If you intend to participate to the challenge, make sure
to also come to the workshop to hear some scary stories.

## How to enter the challenge ?

The only mandatory condition to enter the challenge is to have published a
scientific article before January 1st 2010 and this article must have some
computational aspects (i.e. code).

* **Step 1** You need to declare your interest in the challenge by posting on
  this [GitHub issue](https://github.com/ReScience/ten-years/issues/1) the
  article you intend to reproduce (having your article open access would be
  great). This does not engage you in any way.  We'll only use this GitHub
  thread to gently spam you with a few reminders when we'll be close to the
  deadline (01/04/2020).

* **Step 2** You have to try to make your old code run on your current
  machine, documenting in the process what is necessary to make it work. For
  example, you may have to downgrade your system or some libraries, to modify
  your original code because some library is nowhere to be found, to reinstall a
  specific compiler or interpreter, etc. In the end, there may be large number
  of different situations: you are unable to run or compile the code, you are
  able to run the code but it does not give you the expected results (or no
  result at all), the program crashed regularly (before getting results), you
  do not remember how to run your program, etc.

* **Step 3** You have to write a reproducibility report for ReScience (any
  number of pages) and submit it. You'll have to indicate that this submission
  is for the ten years special issue.

* **Step 4** Interact with reviewers during the open peer review and have your
  article published open access (no APC, ReScience is free to read and free to
  publish).

* **Step 5** Come to visit us in Bordeaux and attend the workshop in June (date
  not yet settled) where we'll introduce the results of the challenge. We'll
  also have a bunch of great talks on reproducibility and replicability.


## Frequently Asked Questions

**Is there a prize for the challenge?** Yes, you will get all our
consideration. More seriously, there is nothing to gain but insight on
the reasons why a code becomes non reproducible. We can also send you a print of
the cool poster above (A2 format).

**Can I run the code from someone else?** No, because we want original authors
to re-run their own code. However, if you're interested in trying to run code
from someone else, you can submit a "reproducibility report" that will be
published in a regular issue of ReScience (if accepted after open peer-review).

**I cannot find my source code, can I enter the challenge?** It mostly depends
if you have a good story to explain why you do not have your code anymore.
Writing an article just to say you failed because you did not find the code
does not sound very exciting. But still, we would like to hear from you. Be
assured you're certainly not the only one in that situation.

**My original code has been used, converted, modified, upgraded and I'm sure it
is reproducible** That's good. But what about the original version of the code,
the one you wrote for your article ? This is this code we want to put to the
test.

**Is it ok to submit an article stating I cannot reproduce my results?**
Yes. We actually expect this case to correspond to the majority of
situations. There are many possible reasons and we're interested in knowing
the exact reasons that prevented you from getting your original results.

**Is it ok to submit a one page article stating everything ran fine?**
Yes. But you'll need to give us some details on how you did it (what language,
what OS, how are you sure you get the same results, etc.). This will serve for
a study on what are the *best* languages, libraries, and tools for reproducibility.


## Resources

* The [Wayback Machine](https://archive.org/) is a digital archive of the World
  Wide Web and other information on the Internet. It was launched in 2001 by
  the Internet Archive, a nonprofit organization based in San Francisco,
  California, United States.
  
* [Software Heritage](https://www.softwareheritage.org)'s ambition is to collect,
  preserve, and share all software that is publicly available in source code
  form. On this foundation, a wealth of applications can be built, ranging from
  cultural heritage to industry and research.
  
* [Guix](https://guix.gnu.org/) supports transactional upgrades and roll-backs,
  unprivileged package management, and more. When used as a standalone
  distribution, Guix supports declarative system configuration for transparent
  and reproducible operating systems.
  
* The [National Museum of Computing](https://www.tnmoc.org/) is home to the
  world's largest collection of working historic computers.

* [3.5" Floppy Disk
  readers](https://www.amazon.com/floppy-disk-reader/s?k=floppy+disk+reader),
  [Compat Disc readers](https://www.amazon.com/usb-cd-reader/s?k=usb+cd+reader)
  (on Amazon). Just in case you source code is only available on one of this
  archaic supports...

* [Debian](http://debian.org) provides an
  [archive](http://archive.debian.org) of the packages for the [past
  releases (since 1998)](http://archive.debian.org/debian/dists/) and
  [daily snapshots since 2005](http://snapshot.debian.org/), making it
  feasible to find old versions of software of interest and
  [debootstrap](https://wiki.debian.org/Debootstrap) old environments.
  [NeuroDebian](http://neuro.debian.net) also provides
  [snapshots of the repository since Sep 2010](http://snapshot-neuro.debian.net/archive/neurodebian/).
