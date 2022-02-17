# How to improve Woocommerce Documentation for Developers

Issues with state of Developer Documentaion right now:

1. **Can't Contribute**
2. **Structure**
3. **Gaps**
4. **Outdated**


## Can't Contribute

Developer Documentation should be moved to a 'Docs' folder inside the https://github.com/woocommerce/woocommerce and it should be just simple 'Markdown' files. So anyone can make changes and send a PR. It will make it easier for normal folks to send small, simple PRs for things, like fixing a typo(I have come across a few already), updating outdated URLs and also in general to contribute to docs. Right now Docs is a mish-mash of Wordpress pages, auto-generated docs (PHP Docs, Storybook) and Github Wiki. Lots of very useful documentation is still in Github Wiki and people can't send PRs for Wiki, so basically people can't contribute to docs at all right now. It's time to have a separate Docs team (A separate Docs channel on Slack even!) and separate 'Docs' folder in the Woocommerce Repo. Can ofcourse take the 'feature plugin' route as is happening with 'Admin' and 'Blocks' repo right now.

## Structure

It's not easy to find and navigate docs currently. On https://woocommerce.com/documentation/, I find Developer Documentation section at the bottom. I click on Codex page to be taken to https://woocommerce.com/documentation/plugins/woocommerce/woocommerce-codex/, where I almost drown in all those links and can't figure out where to go next. Finally I figure out that 'Version Notes' section is what I need and 'WooCommerce Developer Wiki' is the link I should select. There I should probably have seen 'Database Description' & 'CRUD Objects in 3.0' at the top but anyways. I click on those links and I am taken to Github Wiki now, where I see the a very good Database Description page. From here I can really start diving into Woocommerce docs. Took 4-5 clicks to reach here :-)

Also the Codex section on https://woocommerce.com/documentation/ has another useful link - https://woocommerce.com/document/class-reference/ but then if you click 'See All Topics', you don't see any link for this. So this page with 'Common Classes' is useful even if looks incomplete and half-backed currently. If you want to see all the classes, you are taken to - https://woocommerce.github.io/code-reference/ which is an auto generated page by PHP Doc. Mostly it appears like to be an index with just the names of classes, functions et. el, with no description or usage given. Needless to say massive scope of improvement here.

If you start your journy from https://developer.woocommerce.com, you will have to scroll down to 'Reference Docs', where you will find links to 'Core Api' but no mention of Github Wiki or Class Reference pages here. So someone starting their journy from here will just miss Github Wiki altogether.

## Gaps

I was searching for 'woocommerce_admin_order_preview_actions' in the Hooks Reference https://woocommerce.github.io/code-reference/hooks/hooks.html, but it's not listed there. I started a conversation on slack about it and offered to help but finally found out there is no easy way to contribute to docs, and my discussion with core team and some enthuasistic woo users and contributors on Slack finally led to this Readme file. This is just one example of a gap in the documentation but there are many like this. I do notice that every blog post about a new Release outlines new actions and filters clearly. However I am not sure there is a process to also update the docs with these new actions and filters at the same time? 

## Outdated

[Structured data for products](https://github.com/woocommerce/woocommerce/wiki/Structured-data-for-products) page was last updated in 2019 and link to 'Google structured data testing tool' should actually now point to - https://search.google.com/test/rich-results in my opinon. Just a simple example, but there are many such examples. Such obscure pages get lost in the sea of the all those pages and understandably can become outdated. However with community participation, such pages can be updated easily and regularly. I would have sent a PR last year, if I could, but alas it's wiki.

---
### Let's make it Happen - Five for the Future.

Please leave your thoughts as comment, start a discussion. Edit this document by sending a PR. Let's arrive on a consensus about the way forward and then, we all can get to work. It may be by way of creating issues in existing Woo repo, or starting a new docs repo (maybe even this repo). This will be a huge undertaking and couldn't be undertaken without the support from core team, community and lots of contributors. Let's see where it goes :-)
