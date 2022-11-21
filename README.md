# justinjbird.github.io

## Info

Page to validate Mastodon profile. Original blog here;

* https://til.simonwillison.net/mastodon/verifying-github-on-mastodon

## How to set up

* clone the repo into {your github user name}.github.io
* replace github.com/justinjbird references with your github username
* replace https://data-folks.masto.host/@justinjbird with address to your mastodon profile
* once committed, {your github username}.github.io should redirect back to your github profile
* add {your github username}.github.io as your github link on Mastodon (NOT your github.com/{username} url)

## Notes

* didn't realise this until after lots of troubleshooting :( you can't have the link set up with Mastodon before things are set up with Github, it won't verify. If you do it in reverse, remove the link and re-add for the verification to happen.
