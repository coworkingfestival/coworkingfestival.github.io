## Requirements
* You need a version of the Ruby programming language on your computer to do this, its installed on every Mac by default.
* You will need to install the xcode command line tools with `xcode-select --install`
* The site is generated with a static site generator. To install it type `gem install bundler jekyll`.


## Usage

To see the site on your laptop start the site generator with `jekyll serve --live`.
It will start a webserver so you can open it in your browser at http://127.0.0.1:4000.

See how to work with files at https://jekyllrb.com/docs/pages/.

### Editing Schedule

Open the csv file called e.g. `monday-events.csv` for the progamm day under `data` in a speardsheet program and make the changes. Save them and send them with `git commit -am 'schedule update' & git push`.