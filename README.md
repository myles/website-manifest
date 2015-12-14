# Web `{Sites,Services,Apps}` Manifest

This is where I store the [git-repo](https://gerrit.googlesource.com/git-repo) manifest file for for all of my website git repositories.

## Requirements

There are two requirements Git and git-repo. You can install git-repo on Homebrew with `brew install repo` and on Linux please see the [the Android documentation](http://source.android.com/source/downloading.html#installing-repo).

## Usage

	$ repo init -u "git@github.com:myles/website-manifest.git"
	$ repo sync
