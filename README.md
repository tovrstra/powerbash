# powerbash

See https://github.com/napalm255/powerbash for the original README.

This branch merges some pull requests of use to me

Installation by hand:

```bash
cd ~/.local/
git clone git@github.com:napalm255/powerbash.git
git remote add tovrstra git@github.com:tovrstra/powerbash.git
git fetch tovrstra
git checkout main
```

Add to `.bashrc` (after direnv):

```bash
source ~/.local/powerbash/powerbash.sh
```
