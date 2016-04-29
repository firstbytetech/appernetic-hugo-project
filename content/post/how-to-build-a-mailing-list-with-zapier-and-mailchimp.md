+++
author = "author"
date = "2016-04-29T15:46:20Z"
description = "description"
draft = true
keywords = ["Appernetic static site generator", "How to", "Hugo", "Zapier"]
tags = ["Zapier", "MailChimp", "MailMunch", "SumoMe"]
title = "How to build a mailing list with Zapier and MailChimp"
topics = ["How-to"]
type = "post"

+++

> on to collect some e-mails for the upcoming launch.
> 
> What's a good ready-made solution for this (e.g. WordPress plugin,
> hosted landing page, etc.) that allows for easy lead collection
> without custom coding or monthly fee?"

That was the question I saw in the 7 Day Startup group on Facebook. Similar questions were asked in Hugo Community discuss : Is it possible to add a contact form to a site?

It seems to be a common pain point.

With a static website, you don't have anything that can process form submissions so it is not a simple task to do it yourself. 

For this, you need a newsletter opt-in form, a mailing list and a service that handles the submitted content.

In our latest theme: [hugo-bootstrap-premium][1] we have integrated a newsletter opt-in form that is super easy to customize without any coding.

![enter image description here][2]

You only have to enable the form and add your [Zapier][3] post hook that's post to [MailChimp][4] to use it. 

![Appernetic.io Newsletter opt-in form with Zapier hook][5]
This is how the enabled newsletter opt-in form with a Zapier hook
We also integrated [MailMunch][6] and [SumoMe][7] so you can use it instead  if you prefer.


  [1]: https://github.com/appernetic/hugo-bootstrap-premium
  [2]: https://res.cloudinary.com/appernetic/v1461945240/aaxlgeo4btp4ih5hlhtb
  [3]: https://zapier.com
  [4]: http://mailchimp.com/
  [5]: https://res.cloudinary.com/appernetic/v1461945371/jdx7evqmqmrli2ib7wzf
  [6]: https://www.mailmunch.co/
  [7]: https://sumome.com/