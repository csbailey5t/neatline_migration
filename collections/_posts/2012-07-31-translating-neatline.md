---
title: Translating Neatline
author: Jeremy Boggs
layout: post
permalink: /2012/07/31/translating-neatline/
categories:
  - Neatline News
tags:
  - translations
---
*Cross-posted at the [Scholars&#8217; Lab blog][1].*

If you’re fluent in English and another language, and would love to help with the [Neatline][2] project, please consider contributing a translation for our Neatline plugins!

We’re using a service called Transifex to manage translation work. To get started, just sign up for a free account on Transifex (or log in using your Twitter or Facebook account), then check out our [Neatline project page][3]. If you already see a language listed, just click on it, then request to join that language team to begin contributing. If the language you&#8217;d like to contribute doesn&#8217;t appear on the list, just click the link near the top of the languages list to “Request a new team” and we’ll add that team to the list, and add you to it. Once all that is set up, you can begin adding translations to any (or all!) of our plugins.

Once you’re added to a language team, you can click on that language, and see a list of the resources (i.e., Neatline plugins) we have available to translate. Clicking on any of the resources should bring up a modal window with various options for translating the resource, including a button to “Translate Online”. From there, you’ll be presented with a page that has the English word or phrase on one side, and a text area to contribute a translation on the other.<figure id="attachment_5429" style="width: 1008px;" class="wp-caption alignnone">

<a href="http://www.scholarslab.org/slab-code/translating-neatline/attachment/screen-shot-2012-07-31-at-3-18-19-pm/" rel="attachment wp-att-5429"><img class="size-full wp-image-5429" title="Translation interface on Transifex.net" src="http://www.scholarslab.org/wp-content/uploads/2012/07/Screen-shot-2012-07-31-at-3.18.19-PM.png" alt="" width="1008" height="757" /></a><figcaption class="wp-caption-text">Translation interface on Transifex.net</figcaption></figure> 
Translating static word strings—phrases like “Save your exhibit”, for example—are pretty straight-forward. Occasionally, though, you will run across a string that includes text like %s or %$1s. This text is a placeholder for dynamic content, generated by the Neatline plugin when used in Omeka. To translate strings with these placeholders, simply translate the other words in the string, and move the placeholder text wherever it would make sense for your translation. For example, the string “The timeline &#8220;%s&#8221; was successfully added!” is translated into Spanish as “Se agregó la secuencia &#8220;%s&#8221;!”

The Omeka team also manages their translations through Transifex, and they have some nice [documentation on contributing translations][4] using the platform; if you have questions, try checking their page. Additionally, Transifex also has some nice documentation for many features of their service, including [contributing translations][5].

As translations are completed, we&#8217;ll add them to each plugin&#8217;s `languages` directory before each release. So if you&#8217;d like to see Neatline in a different language, please consider contributing a translation. We appreciate your help in giving Neatline a truly global reach!

 [1]: http://www.scholarslab.org/slab-code/translating-neatline/
 [2]: http://neatline.org
 [3]: https://www.transifex.com/projects/p/neatline/
 [4]: http://omeka.org/codex/Translate_Omeka
 [5]: http://help.transifex.com/intro/translating.html#translating "Documentation for adding translations on Transifex."