# reddark-subinfo

## ARCHIVED

Archived as I think this has now passed the end of its usefulness. Also I'm fairly sure the API changes partially broke [@username-is-required-bot](https://github.com/username-is-required-bot], and I don't have the motivation to try and fix it.

This repository exists to be a home to manually maintained lists of subreddits with specific status(es), originally created for use by [my fork of Reddark](https://github.com/username-is-required/Reddark).

## Current repository uses

### John Oliver
The file [`john-oliver-subs.json`](john-oliver-subs.json) is being used to keep a list of subs that have gone into 'John Oliver' mode -- for example, [r/pics](https://web.archive.org/web/20230618032422/https://old.reddit.com/r/pics/comments/14bai7s/henceforth_rpics_will_feature_only_images_of_john/). If you are aware of a subreddit that has gone full John Oliver but is not included in the list, **please do [submit an issue](https://github.com/username-is-required/reddark-subinfo/issues/new?title=new%20john%20oliver%20sub:%20r/[subname])**!

(Similarly, if a sub is on the list but is *not* in John Oliver mode, please [submit an issue for that](https://github.com/username-is-required/reddark-subinfo/issues/new?title=remove%20sub%20from%20john%20oliver%20list:%20r/%5Bsubname%5D) as well.)

### Banned Subs
The file [`banned-subs.json`](banned-subs.json) is being used to keep a list of subs that are included on the r/ModCoord list of participating subs, but (for whatever reason) have been banned by the Reddit admins.

This list is maintained completely automatically, with a script that should check every 2 hours for new banned subs/subs that are no longer banned. However, if you notice an issue of any sort with this data, please [raise an issue](https://github.com/username-is-required/reddark-subinfo/issues/new?title=banned-subs%20issue:%20%5bdescribe%20issue%5d). 

## Querying a file 

If you wish to set an application to query the most recent version of a list, I've included links to the raw GitHub files below:

 - `john-oliver-subs.json`: https://raw.githubusercontent.com/username-is-required/reddark-subinfo/main/john-oliver-subs.json
 - `banned-subs.json`: https://raw.githubusercontent.com/username-is-required/reddark-subinfo/main/banned-subs.json

## License
The data in this repository is licensed under the [Creative Commons Zero v1.0 Universal license](LICENSE).
