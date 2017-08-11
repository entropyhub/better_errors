# Better Errors

This fork utilises [g2crowds's idea](https://github.com/g2crowd/better_errors)
idea to make page loading faster. We only show the variable values in the
bottom right of the page when the user clicks "Show Variable Values".

### Usage

Be sure to deploy use the `optional-load-env` branch.

See https://github.com/charliesome/better_errors for useage instructions.

### Hacking

If you need to update this gem, I'd suggest setting up your remotes something like this.

```
git remote add upstream  git@github.com:g2crowd/better_errors.git
git remote add upupstream git@github.com:charliesome/better_errors.git
```

You can then pull, merge and rebase new code in.
