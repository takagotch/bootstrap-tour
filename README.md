### bootstrap-tour
---
https://github.com/sorich87/bootstrap-tour

```
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
sudo apt-get update && sudo apt-get install ruby-full yarn

/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install ruby yarn

yarn global add gulp-cli
yarn
gem install jekyll

gulp 
gulp dist
gulp test
gulp docs
gulp clean
gulp server
gulp bump --type minor (major.minor.patch)
```

```js
var tour = new Tour({
  steps: [
  {
    element: "#my-element",
    title: "Title of my step",
    content: "Content of my step"
  },
  {
    element: "#my-other-element",
    title: "Title of my step",
    content: "Content of my step"
  }
]});
tour.init();
tour.start();
```

```
<link href="bootstrap.min.css" rel="stylesheet">
<link href="bootstrap-tour.min.css" rel="stylesheet">
<script src="jquery.min.js"></script>
<script src="bootstrap.min.js"><script>
<script src="bootstrap-tour.min.js"></script>

<link href="bootstrap-tour-standalone.min.css" rel="stylesheet">
<script src="jquery.min.js"></script>
<script src="bootstrap-tour-standalone.min.js"></script>
```

