---
title: Configuring the blog
description: Learn how to configure the blog template
published: false
pubDate: Oct 25 2024
heroImage: /src/assets/blog-placeholder-1.jpg
---
Editing the code: Change the values in `src/config.json` to configure the blog to your liking, see below for more information.

Editing using [pagecms](https://next.pagescms.org): After having logged in and opened your repository, click on "Website Configuration" and fill out the form, changing the values to your liking. Click "Save" to apply the changes (takes about 1 minute to deploy).

## SITE\_TITLE

*   will be shown in the title and meta tags and og image

## SITE\_DESCRIPTION

*   will be shown in the meta tags

## SITE\_FAVICON

*   will be used as the icon in the header and the favicon

## NAME

*   used in the footer (c) YOUR\_NAME

## POSTS\_PER\_PAGE

*   how many posts to show on per paginated page (also used for tag pages)

## MANUAL\_DARK\_MODE

*   should we show the dark mode toggle? (otherwise, it will be based on the user's system preferences)

## SEARCH\_ENABLED

*   should we show the search bar?

## BASE\_COLOR

*   shade of gray for the background one of 'gray', 'neutral', 'stone', 'zinc', 'slate'

## ACCENT\_COLOR

*   color of links, etc. one of 'red', 'orange', 'amber', 'yellow', 'lime', 'green', 'emerald', 'teal', 'cyan', 'sky', 'blue', 'indigo', 'violet', 'purple', 'fuchsia', 'pink', 'rose'

## SOCIAL MEDIA LINKS

*   set any of these to '' to hide the respective icon in the footer
    
*   FACEBOOK\_URL
    
*   TWITTER\_URL
    
*   GITHUB\_URL
    
*   INSTAGRAM\_URL
    
*   LINKEDIN\_URL
    
*   YOUTUBE\_URL
    
*   SUBSTACK\_URL
    
*   EMAIL
    

## MANUAL\_SITE\_BASE

*   set this to true if you want to manually set the site and base url (e.g. when not deploying to github pages)

## SITE

*   will be set automatically when deploying to github pages

## BASE

*   will be set automatically when deploying to github pages