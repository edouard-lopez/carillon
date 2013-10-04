# Carillon

`Carillon` is a minimal, responsive theme for Octopress [based on Greyshade theme](https://github.com/shashankmehta/greyshade)
Starting point forked from [Slash](https://github.com/tommy351/Octopress-Theme-Slash)

##Features

1. Responsive design.
1. Fancybox integration
1. Gravatar support thanks to [Zhigang Fang](https://github.com/zhigang1992). Add your email id to `_config.yml` and your profile picture will appear in the left nav. If you don't want your email to be visible in the HTML code, you can provide the MD5 hashed value of your email as [expected](https://gravatar.com/site/implement/hash/) by Gravatar with an `email_md5` entry in `_config.yml`
1. [Schema.org](http://schema.org/) support thanks to [Nathan Shaughnessy](https://github.com/nathanshox)

##Install

Assuming you have installed the default theme, type the code below in terminal.

    export OCTOPRESS_THEME='carillon'
    git clone git@github.com:edouard-lopez/"$OCTOPRESS_THEME".git
    rake install["$OCTOPRESS_THEME"]
    rake generate

For profile picture and description, just add the relevant details in `_config.yml`

##License

[The MIT License (MIT)](http://opensource.org/licenses/MIT)
