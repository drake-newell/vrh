# vrh
	`vrh` is a simple, `dmenu`-driven void-packages template manager and aggregator. It uses the Github API and basic Linux shell utilities to provide a user-friendly way to download and build selected package templates from any one of the numerous forks of the Void Linux void-packages repository. Unfortunately, due to limitations with the Github API, I have not found a way to search for templates across repositories because Github's search API does not index repository forks with less stars than the original repository. Please note that in order to open the chosen repository in your web browser, you must set the `BROWSER` environment variable.

# Dependencies
* `dmenu`
* `stat`
* `notify-send`
* `curl`
* GNU `sed`
* GNU `grep`
* web browser
* `cp`
* `rm`
* `printf`
* `git`
