Spotify Angular App
===================

This is a sample Spotify app demoing routing through AngularJS, based on [ngRoute example](http://docs.angularjs.org/api/ngRoute.$route#example).

Routing in Spotify Apps is normally carried out throough Spotify URIs (spotify:app:<myapp>:<something_else>). For AngularJS to work properly with these, `ngRoute` and `$location` need to be modified.

However, you can use _normal_ hashbang navigation in a Spotify App that AngularJS understands without overriding anything, as the demo shows.

## Installation

 1. Sign up for a [developer account on Spotify](https://developer.spotify.com/technologies/apps/#developer) by logging in and agreeing to the [terms of use](https://developer.spotify.com/technologies/apps/terms-of-use/).
 2. Create the Spotify folder if it doesn't exist already: `~/Spotify` (Mac OS X and Linux) or `My Documents\Spotify` (Windows).
 3. Open the Spotify folder.
 4. Run `git clone git://github.com/spotify/spotify-angular-app`.
 5. Download the [latest version of Spotify](http://spotify.com/download).
 6. Open Spotify and type "spotify:app:spotify-angular" in the search bar (restart Spotify completely in case it doesn't find the App at first).

## TODO

Add custom directives for Views Framework like `<spotify-player>` or `<spotify-listview>`.
