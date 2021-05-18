# `apt-up`

`apt-up` is a `fish` script to run `apt update` and -`upgrade`

## Advantages

- `apt-up` is faster to type
- `apt-up` automatically requests root access if required
- `apt-up` cannot require unwanted interactivity from `sudo` since it sidesteps the timeout by calling `sudo` once
  - I know this isn’t actually an issue, but I personally find it “cleaner” and less “hacky” this way…
