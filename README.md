# HTML Resume

This is my Resume in HTML. You can create your own forking this (or the original from CodeSchool).

## Setup
```
cd HTMLPortfolioProject
npm install
npm start
```

Running `npm start` should open a browser window pointing to `http://localhost:3000`. Now once you make changes to the files under the `/src` directory, your browser will refresh automatically, displaying the newest changes made to the files. This will save you the round trip of saving files and clicking refresh on your browser.

## Deploying

Putting this site up on GitHub pages is a bit different than some other projects because the code is all in the `/src` directory. There’s a nifty way to push this directory to a GitHub branch, which allows you to use GitHub pages with it! Try running this Git command for this project:

```
git subtree push --prefix src origin gh-pages
```

This will push the `src` folder up to GitHub on the `gh-pages` branch. After that, you should be able to open up `http://username.github.io/HTMLPortfolioProject`, where `username` is your GitHub username.
