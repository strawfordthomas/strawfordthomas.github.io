# strawfordthomas.github.io

A straightforward portfolio website based on the [minimal](https://pages-themes.github.io/minimal/) theme. The left hand side panel is used as a menu to navigate between separate scrolling pages on the right. 

## Editing pages

There are separate markdown(.md) files for each page of the website (that is, the separate pieces of content that appear on the right hand side section of the website). Markdown is a very simple scripting langauge that allows you to format writing for the web. For the main part it just looks like writing. 

The kinds of formatting you can add to documents can be seen [here](https://pages-themes.github.io/minimal/). You can put an asterix (\*) on each side of a word to make it *italicised*, or you can use two (\*\*) to make it **bold.**

The hash sign (\#) is used at the start of a line in order to change that text into a heading. One hash gives you the biggest size of heading and six gives you the smallest.

#### Size four heading

##### Size five heading

###### Size six heading

You can also use markdown to format bullet points and lists, but maybe you don't need those here.

Adding links to your text is a matter of putting the word or phrase you want to be the link in \[square brackets]\ and the link itself straight afterwards in brackets, like \[google](http://www.google.com). 

To edit a page, click on it, hit the pencil icon in the top right hand corner and you'll be able to change the text. If you're using markdown formatting and would like to see how it looks before changing anything, there's a preview icon just above the first line of the text you're editing. When you're done, hit the green "Commit changes" button at the bottom of the page. No need to change "Commit directly to the main branch". You can add a description of the changes you've made in the text box, but it's not really necessary. 

When you've made changes, github will automatically re-render the website. This doesn't always happen immediately, but you should be able to see the changes in about 5 minutes (pressing control+F5 to refresh your browser might speed things up a bit).

## What the other files are

Any pages in the "_drafts" folder won't be accessible on the web. So anything you don't want to be live right now can be moved in here.

The Assets folder is a place to put images or other files in. [Links](assets/images/index/rider.jpg) to resources look like:

\[Links](assets/images/index/rider.jpg)\

If you ever wanted to put an image on the website, you can save an image in this folder and use a link like the one above, just preceded by an exclamation mark.

'''
![catttt](assets/images/index/rider.jpg)\
'''

Which looks like:

![catttt](assets/images/index/rider.jpg)

_config.yml is a weird-titled file that controls some of the overall settings for the website. You're less likely to be changing things in here, but there's a couple of fields for Title and Description that change the text right at the top of the left hand side panel. 

The main HTML for the left hand side website panel is in the _layouts folder. Again, you'll probably want to keep most of this. The main thing you might want to change here is the navigation menu. Hopefully when you look at that file, you'll see the section you can change to add or remove menu items. 

To change the typeface and styles across the entire site, you need to change the styles.scss file in the assets folder.  

