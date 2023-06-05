# Tutorial: Create a personal website with Quarto

## Step 1: Fork and rename this GitHub repository

Fork this GitHub repository and rename your repository to
'YourUsername.github.io'. As an example, my username is 'mikediessner' and the
repository is named 'mikediessner.github.io'. This domain is unique to your
GitHub account and you can use it for free.

## Step 2: Install Quarto

The website is rendered with Quarto. You can download Quarto from
[here](https://quarto.org/docs/get-started/). For a tutorial on publishing a
website with Quarto see this [guide](https://quarto.org/docs/websites/).

## Step 3: Update ``_quarto.yml``

In the website section, update title with your name, i.e. "FirstName SirName".
I chose to display the navigation bar (social media links, etc.) on the top
right and let it feature links to my GitHub, Google Scholar, Twitter, LinkedIn, 
and e-mail.

## Step 4: Update ``index.qmd``

The main content of the website is in the ``index.qmd`` file. You can use basic
markdown syntax (see this
[primer](https://quarto.org/docs/authoring/markdown-basics.html)). You can also
delete existing and add new sections. I've included some icons for each section
to give the website some colour. You can find more icons
[here](https://gist.github.com/rxaviers/7360908).

## Step 5: Upload profile picture and favicon

Swap ``profile.jpg`` with one of your pictures. If you choose a different file
name, make sure to also update the name in the 'About section' in the
``index.qmd`` file.

By default the favicon (your website's icon in your browser) is a :laptop:. You
can create you own favicon and substitute it for ``favicon.png``. I made the
favicon with [favicon.io](https://favicon.io), a free service that does not
require an account. If you choose a different name or file extension, make sure
to also update the name in the website section in the ``_quarto.yml`` file. 

## Step 6: Preview and render html

Right now the website is in the Quarto format. You can preview how the final
website will look by typing ``quarto preview`` into the terminal (you have to be
in the directory of your ``_quarto.yml`` file). When you are happy with your
website, you can render it (turn into html) by typing ``quarto render`` into the
terminal.

## Step 7: Push to remote repository

Once you rendered the website, add, commit and push your changes to your remote
GitHub repository.

## Step 8: Enable GitHub Pages

In your GitHub repository, go to Settings > Pages and make sure that under
'Branch' ``main`` and ``/docs`` are selected. After you saved your changes the
website sould appear under 'https://YourUsername.github.io'. 

Enjoy your new website! :tada:.
