#Read Me

## Contents
#### [About](#about-rewind)
##### [Who](#who-rewind)
##### [What](#what-rewind)
##### [Where](#where-rewind)
##### [Why](#why-rewind)
##### [How](#how-rewind)
#### [Notes](#notes-rewind)
##### [Note 1](#note-1-rewind)
##### [Note 2](#note-2-rewind)
#### [Appendix](#appendix-rewind)
##### [.gitattributes](#gitattributes-rewind)
##### [.gitignore](#gitignore-rewind)
##### [.exclude](#exclude-rewind)
________________________________________________________________________________
## About [:rewind:](#read-me)
This repo is about the lack of template creation by the end user for the Airmail.app.
### Who [:rewind:](#read-me)
This is for people who use Airmail.app.

### What [:rewind:](#read-me)
Without a specified email template system design thinking option there is a work around proposed by others.

### Where [:rewind:](#read-me)
http://feedback.airmailapp.com/forums/274948-airmail-mac-2-0/suggestions/5351656-support-for-templates-or-stationery

### Why [:rewind:](#read-me)
I put this out because during the process Airmail.app
* Crashes
* Always "FAILED TO SEND" the first send attempt and the message draft gets ported to the Drafts folder.
* Airmail.app rewrites my CSS and HTML and inserts detritus...
* I just want the stuff I buy to work.

### How [:rewind:](#read-me)
* Create message
* Edit HTML AND CSS
* Save draft
* Wait till draft goes from local to uploaded to utilize "Move To Folder" option
* Select message in Templates folder
* Edit ascii character code detritus and HTML br tags that Airmail.app inserted
* Attempt to send first time using "Send" button or CMD+Enter
* Message send fails or Airmail crashes
* Go to Drafts folder
* Right click shows only "delete" option
* Double click opens message
* Either way click or keyboard to send message usually works unless Airmail crashes again...
* Whiskey Tango Foxfire?

MBP mid-2010, 15-inch, 8 RAM
Mac OS X 10.10.5 (Fresh install on new hard drive 2015.10)
________________________________________________________________________________
## Notes [:rewind:](#read-me)

### Note 1 [:rewind:](#read-me)


### Note 2 [:rewind:](#read-me)

________________________________________________________________________________
## Appendix [:rewind:](#read-me)

### .gitattributes [:rewind:](#read-me)

> Git attribute data also allows you to do some interesting things when exporting an archive of your project.

```markdown
.git                    export-ignore
.gitignore              export-ignore
.gitattributes          export-ignore
.travis.yml             export-ignore
codesniffer.ruleset.xml export-ignore
```

https://git-scm.com/book/en/v2/Customizing-Git-Git-Attributes#Exporting-Your-Repository

### .gitignore [:rewind:](#read-me)


### .exclude [:rewind:](#read-me)
