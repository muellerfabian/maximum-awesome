# Bob's Maximum Awesome

In here you'll find my personal revisions to maximum awesome.  I will attempt
to upstream as much as possible, but some things are personal preferences that
may not be applicable.

![img](https://raw.github.com/wiki/rphan/maximum-awesome/screenshot.png)

# Differences
- [vim-airline](https://github.com/bling/vim-airline)
- Folding support (spacebar will toggle fold state)
- `H` and `L` (mapped to `^` and `$` respectively)

# Installation
1. `$ git clone https://github.com/rphan/maximum-awesome.git`
1. `$ cd maximum-awesome`
1. `$ git checkout rphan-custom`
1. `rake`

# Updating

git pull may not be a fast forward.

Since I'll be tracking upstream and attempting to push changes back, I will
aggressively rebase to ensure consistency.  In the event that you're having
trouble updating, follow these steps:

1. `$ git checkout rphan-custom`
1. `$ git fetch --all`
1. `$ git reset --hard origin/rphan-custom`

# Thanks!

Feel free to reach out if you have any questions or would like to contribute to
my fork.
