PHP Boilr Template
------------------

Boilr template to initialize PHP projects.

## Usage

First, make sure you install [boilr](https://github.com/tmrts/boilr/wiki/Installation) and initialize it:

    bash <(curl https://raw.githubusercontent.com/tmrts/boilr/master/install) && mv ~/bin/boilr /usr/local/bin/ && chmod 755 /usr/local/bin/
    boilr init

Then, download the template:

    boilr template download creads/php-boilr-template php

And apply it to your project

    cd ~/my-project
    boilr template use php .
