We looked around for a good code base to start with, and selected the one George has been looking at from the competition website.

We forked it and set up a github repo, brinign in the data as well.

We spent some time installing various necessary modules and imports. We worked a balance between using modern versions (bc often the ones they used are so old they are no longer supported), and using the old specific versions (like for transformers where they relied heavily on deprecated versions of functions). In the latter case it was possible and easier to use the older version.
We then had to spend some time changing things to fix errors introduced by the new imports and stuff.