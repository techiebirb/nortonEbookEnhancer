# nortonEbookEnhancer
Often times my friends lose their textbook or are away from home, and they don't have the online version (because they forgot to register). I usually send the online version by using some annoying inspect element, but I got tired of this so I made a userscript to make this easier, which then inspired me to make one that makes the formatting of the online book much better.

Yes, I did use Claude to help me.

## Clean EPUB
This script makes it so that:
1. The text takes up more of the screen and isn't super narrow
2. There are indicators showing where each page starts

These affects apply both on the main page and on the "raw" page, which is described below.

## Open Raw Page
This script makes it so that you can open the "raw" textbook section from the main website. All it does is extract the iFrame's URL and open it.
This allows for:
1. Copying and pasting without limits
2. Printing without limits
3. Saving as a PDF (if you have Google Chrome's "Print to PDF" feature)
