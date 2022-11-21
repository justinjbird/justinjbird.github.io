# justinjbird.github.io

## Info

Page to validate Mastodon profile. Credit here;

* https://til.simonwillison.net/mastodon/verifying-github-on-mastodon

## Notes

I didn't realise this until after lots of troubleshooting :( you can't have the link set up in your Mastodon profile before things are set up in Github, it won't verify. If you have done it in reverse, simply remove the link in Mastodon, get Github pages up and running then re-add for the verification to happen.

## How to set up

* clone the repo into {username}.github.io
* replace github.com/justinjbird references with your github username
* replace https://data-folks.masto.host/@justinjbird with address to your mastodon profile
* once committed, {username}.github.io should redirect back to your github profile
* add {username}.github.io as your github link on Mastodon (NOT github.com/{username}!!!)
