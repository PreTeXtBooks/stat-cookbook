The [probability and statistics cookbook][stat-cookbook] contains a succinct
representation of various topics in probability theory and statistics. It
provides a comprehensive mathematical reference reduced to its essence, rather
than aiming for elaborate explanations.

Feel encouraged to extend the cookbook by forking it and submitting pull
requests.

Build Setup
-----------

### LaTeX Version

You can build the LaTeX cookbook locally via:

    make

This first generates the distribution plots via R and then compiles the LaTeX source.
You may have to install a few missing packages via CRAN.

### PreTeXt Version

The PreTeXt version of this book can be built using the PreTeXt CLI:

1. Install PreTeXt CLI:
   ```
   pip install pretextbook
   ```

2. Build the HTML version:
   ```
   pretext build web
   ```

3. View the built book:
   ```
   pretext view web
   ```

The PreTeXt version is automatically built and deployed to GitHub Pages when changes
are pushed to the main branch.

License
-------

This work is licensed under a [Attribution-NonCommercial-ShareAlike 4.0
International License][by-nc-sa].

[![Creative Commons License][by-nc-sa-img]][by-nc-sa]

[stat-cookbook]: http://statistics.zone
[by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[by-nc-sa-img]: http://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png
