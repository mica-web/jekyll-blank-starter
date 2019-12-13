# jekyll-blank-starter
The --blank flag for Jekyll truly creates a blank setup. Use this to get started.

# Installation instructions
Jekyll uses Ruby, so we need to make sure it's on your current machine. First, let's see if you have Ruby on your machine.

## In your terminal:

1. Type `ruby -v` and press enter
1. If you got back a ruby version, then type `rvm -v` and press enter

### No Ruby? Let's get that sorted:

- For **Windows**
 1. Go to https://rubyinstaller.org/
 1. Click the Download button
 1. Download the bold option (described under "Which version to download?")

- For **Mac**, in your terminal
 1. Install RVM GPG Keys by using the first command here http://rvm.io/rvm/install#install-gpg-keys
 1. Install rvm and Ruby by typing
`\curl -sSL https://get.rvm.io | bash -s stable --ruby`
and pressing enter
 1. When the installer is done, repeat the first two commands:
   1. `ruby -v`
   1. `rvm -v`

Once you have confirmed you have Ruby installed, we can carry on.

## On GitHub:

1. Login and create a new repository ([instructions](https://help.github.com/articles/create-a-repo/))
1. Copy the "Clone with HTTPS" link

## In your terminal:

1. Navigate to your **Sites** directory
1. `git clone <your repo URL>`
1. `cd` into the new directory -- from now on, I'll refer to this as your **project folder**
1. `gem install jekyll bundler`
1. `jekyll new . --blank --force`

## On GitHub:

1. Go to https://github.com/mica-web/jekyll-blank-starter
1. From that repo click the "Clone or download" button and choose "Download ZIP"
1. Everything inside the resulting "jekyll-blank-starter" folder should get copied and pasted into project folder (NOTE: This does not include the "jekyll-blank-starter" parent folder.

## In your text editor:

1. Open the project folder
1. Open the `_config.yml` file
1. Change "Your awesome site name" to your first name and save the file

## In your terminal:
1. `bundle exec jekyll serve`

## In your browser:
1. Visit `http://localhost:4000/`

![screenshot](https://trello-attachments.s3.amazonaws.com/5b311619fe69ce00b6e7e155/5b83056971208404ff3bfa74/6a4bb824603cad7d89b2a13891b4c8b6/starter_page.png) 

You should see a page similar to the above screenshot; **ooh la la** very exciting :trophy:

