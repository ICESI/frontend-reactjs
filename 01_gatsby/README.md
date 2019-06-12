# www-gatsby

## Setup environment

```
brew install node
node --version
npm --version
npm install -g gatsby-cli
gatsby --help
```

## Create a hello world application

```
gatsby new [SITE_DIRECTORY_NAME] [URL_OF_STARTER_GITHUB_REPO]
```

```
gatsby new hello-world https://github.com/gatsbyjs/gatsby-starter-hello-world
cd hello-world
gatsby develop
```

To expose the webpage on the local network
```
gatsby develop -- --host=0.0.0.0
```

Run a test
```
curl http://localhost:8000
```
