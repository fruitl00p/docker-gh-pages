# Github pages docker image

This is a `simple` docker image for running the github pages stuff locally (jekyll) in order to speed up gh-pages development

## Usage

Go to your app root and switch to the ```gh-pages``` branch. Afterwards run:
 
```
docker run --rm -ti -v $(pwd):/app -p 4000:4000 gekkie/gh-pages
```

You can now live edit your files locally and watch http://localhost:4000 / localhost.xipio

# Feedback


Please post an issue on the issuetracker!
