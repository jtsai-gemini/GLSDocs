# Title



Apparently Notepad has formatting and can show Markdown syntax... I guess it means you can type things out with formatting and then switch over to Markdown syntax to see essentially the plain text (of what Markdown will look like)?

The real question is if this will save as proper .md files though?

wait wtf yeah it will. why was it giving me issues the other day then. or maybe it was trying to edit an existing .md file??? okay nvm then this should be fine

or maybe it was trying to edit the .yml file lol?

------------------

(the below is me trying this "copy as markdown" option in Google Docs)

## Subtitle

**What is this about?**

This document provides a standardized process for setting up a course in Paylocity for use at Gemini Academy.

-----------------

# Basics

(this is the current Heading 1. it does not translate over to the table of contents on the site, but it's what Google Docs reads as section headers in the internal table of contents (on the left side of the doc))

Actually. Maybe this is something that can be adjusted in the "Material for MkDocs" build somewhere... since there's code behind building the site itself (or the site theme)...? hmm. would have to try and look into that later.

on my list of things to look into:

* figuring out if there's a good way to organize by department (so the "My Docs" section on the left doesn't list every file, but have like directories that can be department-specific)

* methods of moving GDocs files over to Markdown (as painlessly as possible... lol)

The good news is that it's actually pretty easy to test how the page looks while editing (run the mkdocs serve, open the .md file, make edits, hit save, and then see the page update in real time). Kind of a fun way to play around with Markdown in real time

But yeah, need to figure out the stuff on my list first, to see how viable this would be.... if it does work, then the next big thing to consider is how to maintain things. I still think we could just make sure people continue to edit on Google Docs (so we don't need to ask people to learn markdown or anything lol), but it does seem like there'd be a lot of manual formatting work to do for maintenance... also image hosting seems like its own beast, so to speak.

Of course, I think it'd be better if we could lessen the amount of images that are used, but that's probably a consideration for later... (but if we have Whatfix working as intended, then maybe we don't need to have so many images? something to consider)

Update: PHEW okay actually I was able to modify the configuration to have the table of contents read the Headings (subtitles get nested)

