## Fork the repo(sitory) from GitHub

Log into your GitHub account.  Now go to the website repo: https://github.com/BioData-Club/jekyll-academic and click the **Fork** button on the top right of the webpage.

When we fork we're copying the files into our own repository.  We'll use the copy as the building block for your new website.

## Rename the repo

Now click the **Settings** tab on your repository. Change your repository name to USERNAME.github.io, where USERNAME is your GitHub account name.

## Editing the name of your webpage

The first step to personalizing your website is to edit the information in the YAML file.  This is a configuration file where some important settings for your site are stored.

You'll find the `_config.yml` file in the root (parent) level of your repo. In GitHub, click on the `_config.yml` file.  To edit it click on the pencil button on the right.

Update the *title*, *name*, *bio*, *email*, and the social media fields you want (such as *twitter*, *linkedin*) with your information.

Just make you that you don't modify anything below `#DO NOT EDIT BEYOND THIS POINT`.

Here's an example `_config.yml` file. Don't worry about the avatar and the logo file for right now. # symbols are the beginning of comments.  The text to the right of any **#** symbol is ignored.  

```
# Site wide configuration

title: Academic Website of Ted Laderas
locale: en_US
logo: # filename of a logo image that has been placed into your images directory

# Enter the following platform usernames if you would like for them to appear on your site.
owner:
  name: Ted Laderas
  avatar: bio-photo.jpg
  bio: "This is a sample Jekyll academic website."
  email: laderast@ohsu.edu
  # Do not include the @ symbol in your Twitter username
  twitter: laderast
  linkedin: #username
  github: laderast
  orcid: # ID Number (ex. 0000-0000-0000-0000)
  researchgate: #username
  mendeley: #username
  google:
    plus: #username
    analytics:
    verify:
    scholar: #id
```

After you have edited your `_config.yml` file, click the green **Commit changes** button at the bottom of the page, which will save the file changes in your repository.

## Look at your new website!

You're ready to go!  Check out your initialized website at https://USERNAME.github.io. Next we will [add a bio](workshop/your-bio)!

## A little bit about Jekyll

Jekyll is what's known as a static site generator. It will build a website from simple text files that are in Markdown.  Markdown is much easier to work with, since you don't have to worry about adding HTML tags and accidentally breaking it.

The other nice thing about Jekyll is that it will integrate things like Google Analytics, tags, and search into your website structure.

Jekyll is built into GitHub, so you just need to edit the files in your repository to have GitHub automatically build the webpage.
