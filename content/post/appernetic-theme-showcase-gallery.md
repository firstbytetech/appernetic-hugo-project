+++
author = "Göran Svensson"
date = "2016-06-01T12:04:58Z"
#description = "description"
draft = false
keywords = ["Static website service", "static website", "Hugo", "Theme showcase gallery"]
tags = ["Static website service", "Hugo", "Theme showcase gallery", "static website"]
title = "Appernetic theme showcase gallery"
topics = ["Static website"]
type = "post"

+++
![Setup wizard, now with theme showcase gallery in appernetic dashboard][1]
***The theme showcase gallery is ready! Now you can browse the gallery and install a theme just by clicking on it. This is the themes listed at [Hugo Theme Showcase][2].*** 

## Aggregated meta information
We automatically aggregate and build a JSON file each week that contains the extracted meta information from each of the 86 themes. 

I also check if each theme has an exampleSite folder and a config.toml file and if they have we give them a star in the frontend. 

Everything is served as a JSON file from a REST API endpoint, then we have Angular mangling the arrays and objects to make them look intelligible to us humans.   

If you are not the most patient type of person, avoid themes that have no star, they  need some extra attention to get your website working.

Included in each theme listing is:

 - List item
 - Thumbnail image
 - Theme name
 - Description
 - Author (with website URL)
 - Repository link
 - Minimum Hugo version (which the theme works with).
 - Licence
 - Features/Tags (blue and green labels)  

With the aggregated meta information and the themes gallery ready it was now also possible to include the one-click theme install feature in the quick start wizard.  This will make it much easier to get started.

![Theme showcase gallery item in appernetic dashboard][3]

Click on the dashboard link up to the right and see for yourself and build a [static website][4]!

![Theme showcase gallery item in appernetic dashboard][5]

By the way, I have just removed Twitter user sign-in. It was an easy decision. Twitter users had no email in their meta info and was lagging behind in the interwebs, and behaved inconsistently. Also, I had no Twitter freemium or paying users and I had exceeded Auth0's social connection limits anyway.
 
  [1]: https://res.cloudinary.com/appernetic/v1464414173/suli8vdkjsw9luw1ol3f
  [2]: http://themes.gohugo.io/
  [3]: https://res.cloudinary.com/appernetic/v1464371347/mgc1lnbrytafkitsjmma
  [4]: https://appernetic.io/app/#/dashboard/list/create
  [5]: https://res.cloudinary.com/appernetic/v1464415618/eiysait32vipexfyhduh
