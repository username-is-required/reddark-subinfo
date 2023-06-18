# reddark-subinfo

This repository exists to be a home to 'hard-coded' lists of subreddits with specific status(es), created for use by [my fork of Reddark](https://github.com/username-is-required/Reddark).

## Current repository uses
The file [`john-oliver-subs.json`](john-oliver-subs.json) is being used to keep a list of subs that have gone into 'John Oliver' mode -- for example, [r/pics](https://web.archive.org/web/20230618032422/https://old.reddit.com/r/pics/comments/14bai7s/henceforth_rpics_will_feature_only_images_of_john/). If you are aware of a subreddit that has gone full John Oliver but is not included in the list, **please do [submit an issue](https://github.com/username-is-required/reddark-subinfo/issues/new?title=new%20john%20oliver%20sub:%20r/[subname])**!

(Similarly, if a sub is on the list but is *not* in John Oliver mode, please [submit an issue for that](https://github.com/username-is-required/reddark-subinfo/issues/new?title=remove%20sub%20from%20%john%20oliver%20list:%20r/%5Bsubname%5D) as well.)

## Querying a file 

I have found that jsDelivr provide a CDN for files on GitHub. Therefore, if you wish to set an application to query the most recent version of a list, i've included such links below:

 - `john-oliver-subs.json`: https://cdn.jsdelivr.net/gh/username-is-required/reddark-subinfo@main/john-oliver-subs.json
