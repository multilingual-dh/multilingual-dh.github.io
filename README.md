## Multilingual Digital Humanities website

This repo is for the website of the *Multilingual Digital Humanities* group. Anyone with an interest in using digital humanities tools and methodologies non-English (and non-Latin-script) languages is welcome to [join the mailing list](https://mailman.stanford.edu/mailman/listinfo/multilingual-dh).

The site is built with Jekyll. 

## Issues with a translation? 

If you see an issue with some existing text, or code, whether it's a translation error, or something else, please open a new issue via the issues tab above.

Then, please fork the repo, make whatever edits you feel are necessary, and submit a pull request.

## How to add a new translation

1. Create a new folder in the root directory, using the two-letter language code of the language (e.g., `zh` = Mandarin Chinese).
2. Add two lines to [the language switcher in the template](https://github.com/multilingual-dh/multilingual-dh.github.io/blob/master/_layouts/default.html#L33), with that language code. 
3. Modify [the SASS](https://github.com/multilingual-dh/multilingual-dh.github.io/blob/master/css/style.sass#L68) to include the language code. 
