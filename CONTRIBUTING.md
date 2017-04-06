# Contributing #

We welcome and truly appreciate contribution in all forms - issues, pull requests, questions, or fancy examples of apps/elements build on to of your elements.

## Filing bugs

## Developing the element ##

If you would like to start to fiddle with element's code, here is the flow we use.

Make a local clone of this repo: git clone git@github.com:miguelsmuller/visual-radio.git

In order to develop it locally we suggest to use Polymer-CLI tool.

1. Go to the repo's directory: cd visual-radio
2. Install bower & Polymer CLI: $ npm install -g bower polymer-cli
3. Install local dependencies: $ bower install
4. Start development server $ polymer serve
5. Open the demo/preview: http://127.0.0.1:8081/components/visual-radio/

## Contributing Pull Requests ##

1. [Fork it!](https://help.github.com/articles/fork-a-repo/)
2. [Configuring](https://help.github.com/articles/configuring-a-remote-for-a-fork/) a remote for a fork
3. [Syncing](https://help.github.com/articles/syncing-a-fork/) a fork with the latest version
4. Create your feature branch: `git checkout -b issue-123`
5. Commit your changes: `git commit -m 'Commit message'`
6. Push to the branch: `git push origin issue-123`
7. [Submit a pull request](https://help.github.com/articles/using-pull-requests/) :D

#### Before commit, double check your code. Please dude. ####
- Execute a `git pull` to keep your checkout up-to-date
- Invoke a `git diff --cached` before committing
- **NOT COMMIT BEFORE RUNNING THE PROJECT LOCALLY AND SEE THE CHANGES RUNNING**
- **MAKE SURE THE CHANGES WORK**