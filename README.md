# Corona Drupal Theme Distribution

This repository is merely a sample of what the [Aurora compass extension](https://github.com/Snugug/Aurora) will make if you use the Corona distribution. I will update the code every time I make a change within the compass extension.

## How to use

To use, install the compass-aurora gem, as well as [susy](http://susy.oddbird.net). If you are using Ruby gems, this can be acomplished by this line of code:

```
gem install compass-aurora susy
```

Once you have the compass-aurora and susy ruby gems installed, you can create a new Corona sub-theme by executing this within the command-line:
```
compass create [theme-name] -r aurora --using aurora/corona
```

More information can be found on [my blog post on the subject](http://fourkitchens.com/blog/2012/11/13/compass-aurora-corona-oh-my).


## What is Corona?

Corona is part of the [Aurora compass extension](https://github.com/Snugug/Aurora) and is built to be a more robust and full sub-theme for Aurora. It has a more complete partial structure, and more preprocessors ready to be used in the template.php file. It is meant as a good boilerplate to begin advanced theming for a Drupal site with [Aurora](http://www.drupal.org/project/aurora) as the base theme.

## What can I do to contribute?

This repo is merely what the Aurora compass extension spits out. If you have any advice or changes, make them there. If you are unfamiliar with how compass extensions are written, feel free to open an issue and mark me, I will be glad to take a look.
