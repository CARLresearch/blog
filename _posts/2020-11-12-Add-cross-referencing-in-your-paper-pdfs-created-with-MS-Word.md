---
title:  Add cross-referencing in your Research Papers and Pdfs created with MS Word
author: Aditya Jyoti Paul
description: Make your citations, tables and figures more accessible for readers.
categories: [Research Tips, Research, Paper Formatting]
sticky_rank: 2
toc: false
layout: post
comments: true
show_tags: true
search_exclude: false
hide: false
image: images/2020-11-12-Add-cross-referencing-in-your-paper-pdfs-created-with-MS-Word/frontimage.jpg
---

If you're here, you've in all probability written the first draft of your paper and made a pdf for submission to your favorite journal/conference or open-access repository. Congratulations, pat yourself on the back, the hard part is now behind you. In a series of  blog posts, **I'm going to tell you how you can make your articles easier to read and understand and thus get more cited**!

## Okay! So why do we need in-text cross-referencing?

In-text cross referencing is useful whenever you want to make it easier for the reader to reach any position in the document like

- **Citations** to you references in the bibliography section
- **Sections** and sub-sections
- **Tables** and **Figures**
- Sometimes, page numbers (discouraged as it's easy to overlook relevant page numbers that change at a later stage)
- Any other position you wish to jump to

Whenever we write a paper, we are spreading knowledge and it's the duty of a good writer to make the journey as easy, fun and fulfilling for the reader as possible. A big way of doing this will be cross-referencing.

Word's internal cross-referencing feature seems to be quite arcane and complicated to use if you're using some reference manager like Mendeley or Zotero. In this day and age if you're writing papers, you're undoubtedly using some reference manager. I tried finding an easy way to get this internal cross-referencing to work, but couldn't find any. Hence I found a hackish but simple way to get this done and  in a few simple steps. So bear with me.

## Careful !? 

You cannot easily modify these links, once created and modifying the citations with Mendeley or Zotero later will NOT update the cross-referencing, completely messing up your document. Hence please make sure you're doing this as the absolute last stage of typesetting.

Also keep a saved copy, just in the off-chance, you really need to modify the reference list later.

## Great! Tell me how to do it!

In this section, we'll see how we can do cross-referencing for citations in a few simple steps

1. If you're using any reference manager like Mendeley or Zotero, you'd have something called field-codes in your text. You can check it by pressing `Alt+F9`. If you see some weird text appearing, those are field codes and it's recommended to remove them. Select your entire text by pressing `Ctrl+A` and then get rid of them by pressing `Ctrl+Shift+F9`

2. To make it easier to see all in-text citations within square-brackets, it's ideal to highlight all of them and there's an automated way to do this as well as described [here with explanation](https://cybertext.wordpress.com/2011/06/20/word-replace-and-reformat-text-inside-square-brackets-using-wildcards/). In the off-chance the link disappears, I'd reproduce those steps here:

   a. Select all text with Ctrl+A.

   b. Press `Ctrl+H` to open the Find and Replace dialog box.

   c. Click the `More` button.

   d. Select the `Use wildcards` check box an select `All` in the Search dropdown.

   e. Put your cursor into the `Find what` field.

   f. Type the following exactly (or copy it from here): `(\[)(\*)(\])`

   g. Make sure the highlight option is NOT No color.

   h. Click the `Format` button, and select Highlight.

   i. Click on `Replace All`.

   If your citations use parenthesis, instead of square-brackets, use `\((*)\)` in Step f. Why this works can be found [here](https://bioexpressblog.wordpress.com/2014/04/16/highlight-words-enclosed-in-parenthesis-in-ms-word/). This should select anything within parenthesis including non-citations like `(D)`, please ignore those. This does work for compound references like `(Author1 1993; Author2 and Author3 2017)`. Word has a bug where if a search fails, consequent searches might also fail, in that case, the best way is to restart the word processor saving the existing changes.

![Highlight](/images/2020-11-12-Add-cross-referencing-in-your-paper-pdfs-created-with-MS-Word/Highlight.png "Here's how we highlight all our citations.")

   Verify it all looks as expected and proceed.

3. In your Bibliography/References section, click on the first reference, on the part `[1]`, in between the brackets and press `Ctrl+Shift+F5` to insert a bookmark.

4. Name the reference `r01`(to later maintain order for upto 99 references easily) and press `Enter`. 

5. Repeat step 4 for all your references.

6. Now select the part you want to link to say the number 1 between the square brackets, and to add the link, click `Ctrl+K` , select `Place in This Document` in the left and click on the bookmark `r01`. Make sure text to display shows the selected text, ie. the number 1 here.

7. Repeat Step 6 for all highlighted occurrences. For references like [17-19], add only one link from `17-19` to bookmark `r17` and for [37-40,45], add one link from `37-40` to bookmark `r37` and one from `45` to bookmark `r45`.

![Bookmark](/images/2020-11-12-Add-cross-referencing-in-your-paper-pdfs-created-with-MS-Word/Bookmark.png " Here's how we create a Bookmark.")

8. Remove all the highlights and probably the blue link decorations with blue fonts and underlines as well. Research papers have uniform font settings. So select `Ctrl+A`, remove the highlights, select the font color as Black and press `Ctrl+U` twice to remove underlines.

Here we've primarily covered only cross-referencing citations with references, but this can be easily extended to sections, subsections, tables, figures or any other place in the document by bookmarking at that location with `Ctrl+Shift+F5` , naming it and pressing `Enter`. Then just go to the place where the link should originate and press `Ctrl+K` and add the destination as the correct bookmark. I usually use the naming convention of `r01...` for references, `f01...` for figures, `t01...` for tables, `s01...` for sections and `ss01...` for sub-sections, but feel free to use any convention you want.

## Here are some researchers and their Papers using this Method

- [A. J. Paul](https://orcid.org/0000-0002-4351-2108), “[Randomised fast no-loss expert system to play tic-tac-toe like a human](https://arxiv.org/abs/2009.11225v2),” Cogn. Comput. Syst., Sep. 2020, doi: [10.1049/ccs.2020.0018](https://doi.org/10.1049/ccs.2020.0018). (Click on the paper title to reach the ArXiv version of the paper typeset by the author)

  *and many more to come!!*

## Congratulations !!

***You've made your first cross-referenced pdf in MS Word!*** Do note cross-referencing might appear to work on some mobile pdf viewers even if it is enabled in the pdf, but does work on the Desktop, with Adobe, Google Chrome etc.

If you know such a free tool exists to do this for MS Word documents, do drop it in the comments, and we'd love to mention it here. In future, someone might create a script/macro for this, making it even easier. If you create that, or know someone who does, do reach out to us in the comments, we'd love to give it a shoutout and even go and make a post about it benefitting researchers across the globe.

***Finally, if this article helped you, we'd love to hear about it in the comments and if you have used it in a paper, we'd love to feature your paper here as well.***
