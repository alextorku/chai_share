# CHAI Share

Public repo for code from the University of Michigan's [CHAI Lab](http://web.eecs.umich.edu/~emilykmp/chai/people.html). The repo is organized as follows:

* [Bins](Bins) - executable stand-alone scripts and binaries
* [Libs](Libs) - libraries that can be used within your own code

## Setup

First, clone the repository:

```
git clone git@github.com:ducle90/chai_share.git
```

Then, expose the repository's location through `~/.bashrc` (or an equivalent
file like `~/.bash_profile`). To do so, add this line to the TOP of the file:

```
export CHAI_SHARE_PATH=/path/to/chai_share
```

Replace `/path/to/chai_share` with the actual path, such as `/home/ducle/chai_share`. From your terminal, run:

```
source ~/.bashrc
echo $CHAI_SHARE_PATH
```

If you see the path printed on the screen, you're all set! Remember that this
is only the first installation step. To use certain binaries/libraries, you'll
have to follow their specific installation guide.
