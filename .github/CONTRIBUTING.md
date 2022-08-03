## Development Environment

Fork this repository and clone it locally.

`git clone https://github.com/{username}/animethemes-encoding-scripts.git`

Set this repository as upstream to your fork.

`git remote add upstream https://github.com/AnimeThemes/animethemes-server.git`

Pull upstream changes so that your local branch is even with upstream.

`git pull upstream main`

Push upstream changes to your remote if needed.

`git push`

## Feature Branch Workflow

Once your main branch is even with upstream, create feature branch from the main branch.

`git branch new-feature-branch`

Switch to feature branch.

`git checkout new-feature-branch`

Make changes in feature branch.

Stage changes. Commit changes. Please include ticket ID's and use [Semantic Commit Messages](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716).

## Pull Request

Push changes to remote.

`git push --set-upstream origin new-feature-branch`

Create Pull Request from your new feature branch to upstream main branch.

## Pruning

Once the Pull Request is merged, delete the feature branch locally.

`git branch --delete new-feature-branch`

Delete the remote feature branch.

`git push origin --delete new-feature-branch`

Pull upstream changes so that your local branch is even with upstream.

`git pull upstream main`

Push upstream changes to your remote if needed.

`git push`

## References

* [Semantic Commit Messages](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716)
* [Github Forking](https://gist.github.com/Chaser324/ce0505fbed06b947d962)