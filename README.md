## Hugo (the main page)
[https://gohugo.io/](https://gohugo.io/)

## Getting Started
[https://gohugo.io/getting-started/quick-start/](https://gohugo.io/getting-started/quick-start/)

Navigate to "prebuilt binaries" or
[https://gohugo.io/getting-started/quick-start/](https://gohugo.io/getting-started/quick-start/)

Choose the "hugo_extended" version for your OS, download, and unzip it.

Extended seems to be required for anything interesting you'd like to do with a theme, so just bite the bullet.

I moved this to the Desktop and renamed it just "hugo" for simplicity

Then you can add to PATH with

export PATH=$PATH:~/Desktop/hugo/

(May need to RESTART your terminal if there are issues)

[https://nordvpn.com/blog/macos-cannot-verify-this-app-is-free-from-malware/](https://nordvpn.com/blog/macos-cannot-verify-this-app-is-free-from-malware/)

Open up “System settings.”
2.

Find the “Privacy & security” tab on the left side and click on it.
3.

Scroll down to the “Security” section and look for “Allow applications downloaded from

click "Allow anyway"

type 

hugo version 

to check your installation

## Hugo Themes

Although you can build a hugo site completely from scratch, themes allow you to quickly apply a look and structure to your site.

[https://themes.gohugo.io/](https://themes.gohugo.io/)

You can experiement with other themes too, but we'll use "jughead" since it appears to just work out of the box without any other tweaks.

[https://themes.gohugo.io/themes/jughead/](https://themes.gohugo.io/themes/jughead/)

download it and unzip it (or git clone if you prefer)

cd to examplesite

The theme expects git to be present so run the following commands.  (This tutorial will not go into detail about git or github)

git init
git add *
git commit -m "first commit"

We may also need to put the theme itself in the themes directory of the example site. 
mkdir themes
cd to it and 

git clone https://github.com/ananthb/jughead

We should now have a working setup. 

Running "hugo" will rebuild the site. 

Running "hugo server" will generate a locally built copy.


RENDER

We will use Render to quickly spin up a site. Render can read directly from a github repo.

[https://render.com](https://render.com)

Create an account.

Click "Configure and Deploy Static Site", link to your github and you're done!

For github, the "use public repo" is a simple option

./ is build directory if you have only pushed the public files


----

Adritian
https://github.com/zetxek/adritian-free-hugo-theme/archive/refs/heads/main.zip
