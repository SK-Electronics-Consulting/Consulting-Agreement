# Consulting Agreement

## Background
This is meant to be a consulting agreement template to quickly generate a consulting agreement PDF, which can be submitted to HelloSign/Docusign/etc. for signatures.

It is written in Linux, and is based off a consulting agreement found online.  (TODO: find source link.)

The intention is to make a clean agreement document that hides all the checkboxes and options, and strictly keeps the applicable clauses.  It also formats things nicely without requiring much post-processing.

## How To Use

Adjust the information in the clientinfo.tex file, and regenerate.

Select options using the \toggletrue and \togglefalse statements within clientinfo.tex. 

## Caveats

* The actual PDF will not be included in this repo, as that will contain customer information.  
* Using the commands to fill in the fields requires that each command end with a space.  This is just a weirdness of LaTeX, and it would be great to solve somehow.
