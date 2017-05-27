#HSLIDE

### Learning gitpitch

* Read the [devco
  newsletter](http://us14.campaign-archive1.com/home/?u=48a10a5d8254d034473c9ca1c&id=38d0f6d5e9) from 05.03.2017 with R.I. Pienaars ramblings
* Visit [the gitpitch Homepage](www.gitpitch.com) and view the slideshow
* Ignore all the marketing talk and get <a href="https://github.com/gitpitch/gitpitch/wiki" target="_blank">the real documentation</a>

#HSLIDE

### Start with a simple Slide

* `mkdir ~/repos/learning-gitpitch && cd ~/repos/learning-gitpitch && git init &&
  vim PITCHME.md`

```
#HSLIDE

### Learning gitpitch

* Read the [devco
  newsletter](http://us14.campaign-archive1.com/home/?u=48a10a5d8254d034473c9ca1c&id=38d0f6d5e9) from 05.03.2017 with R.I. Pienaars ramblings
* Visit [the gitpitch Homepage](www.gitpitch.com) and view the slideshow
* Ignore all the marketing talk and get <a href="https://github.com/gitpitch/gitpitch/wiki" target="_blank">the real documentation</a>
```

* `git add PITCHME.md && git commit -m'First steps documentation with gitpitch'
  && git remote add origin https://github.com/Arabus/learning-gitpitch.git &&
  git push --set-upstream origin master`

