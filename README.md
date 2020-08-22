# mixed-content-bulk-checker
[Chrome started blocking](https://security.googleblog.com/2019/10/no-more-mixed-messages-about-https_3.html) "mixed content" earlier this year, meaning that https:// pages can only load secure https:// subresources.  But don't panic! This Python script can help you!  🙌  What it does:  *   Loops through all your URLs *   Spots "Mixed Content" errors from the Chrome Console Log *   Exports the results in a CSV file!  Kudos to [@allophonousrex](https://twitter.com/allophonousrex) for the original script, which can be found [here](https://github.com/DeepCrawlSEO/public/blob/master/Chrome%20Mixed%20Content%20Errors%20Fetch%20v1.2.ipynb). The current script adds a few tweaks, such as:  *   Installs Selenium + Chromium in the Cloud, so it works out of the box in Google Colab *   Auto-imports CSV file via Widget *   Auto-adjusts fetching speed   Caveat: The script *should* work well on large files, though it has yet to be tested on a list larger than 10k URLs.  Enjoy!

[Chrome started blocking](https://security.googleblog.com/2019/10/no-more-mixed-messages-about-https_3.html) "mixed content" earlier this year, meaning that https:// pages can only load secure https:// subresources.

But don't panic! This Python script can help you!  🙌

What it does:

*   Loops through all your URLs
*   Spots "Mixed Content" errors from the Chrome Console Log
*   Exports the results in a CSV file!

Kudos to [@allophonousrex](https://twitter.com/allophonousrex) for the original script, which can be found [here](https://github.com/DeepCrawlSEO/public/blob/master/Chrome%20Mixed%20Content%20Errors%20Fetch%20v1.2.ipynb). The current script adds a few tweaks, such as:

*   Installs Selenium + Chromium in the Cloud, so it works out of the box in Google Colab
*   Auto-imports CSV file via Widget
*   Auto-adjusts fetching speed 

Caveat: The script *should* work well on large files, though it has yet to be tested on a list larger than 10k URLs.

Enjoy!
