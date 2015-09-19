# WebHare example site

This is the example module that is installed when you run `wh setupdev`. It
also contains the data for the example site in 'data/Example site.zip'.

This site is extracted by setupdev whenever the example site is completely empty,
and you can update this zip if you need to update the contents of the Example site.

setupdev removes the git remote origin after extracting it, preventing users
from trying to push it. If you need to submit modifications to the whexample_site
module, you'll need to readd the git remote - execute this in the root of the
module:

`git remote add origin git@gitlab.b-lex.com/webhare.net/whexample_site.git`
