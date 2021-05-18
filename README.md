# `apt-up`

`apt-up` is a `fish` script to run `apt update` and -`upgrade`

## Advantages

- `apt-up` is faster to type
- `apt-up` automatically requests root access if required
- `apt-up` cannot prompt again via `sudo` since it sidesteps the timeout by calling `sudo` only once
  - I know this isn’t actually an issue, but I personally find it “cleaner” and less “hacky” this way…
