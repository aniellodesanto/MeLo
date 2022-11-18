# MeLo lab page

This is repository for the Mathematics of Language and cOgnition at the University of Utah. The sourcecode is a modified version of the [Kording lab page](http://kordinglab.com/) repo, which is itself adapted from [Bedford lab page](https://bedford.io/). Many thanks to both for making their code available. The page is run via Jekyll.

## Run the page locally using Jekyll

To run locally, follow instruction [here](https://jekyllrb.com/) to install Jekyll then run `jekyll serve` to see in `localhost:4000`. Here is a brief install guidelines.

```bash
sudo gem install jekyll
sudo gem install rouge
jekyll serve
```

The Bedford Lab repo readme has also some good throubleshooting tips if you are having trouble installing Jekyll. If you are running the newest versions of Mac OS you might also have problems with Ruby. For example, `jekyll serve` needs `webrick`, which is no longer a bundled gem in Ruby 3.0. [Here](https://github.com/jekyll/jekyll/issues/8523) a tip on how to solve that. For additional issues with Ruby on Mac I suggest you start from [here]( https://www.moncefbelyamani.com/how-to-install-xcode-homebrew-git-rvm-ruby-on-mac/#start-here-if-you-choose-the-long-and-manual-route).
