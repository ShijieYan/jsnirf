# JSNIRF Format Specification Development Guide

We use this repository to gather feedback from the community regarding the 
["JSNIRF Format Specification"](JSNIRF_specification.md), or JSNIRF format. Such 
feedback is crucial to finalize this file specification and help improve
it in the future once disseminated. 

The latest version of the JSNIRF specification can be found in the file named 
[JSNIRF_specification.md](JSNIRF_specification.md). The specification is written
in the [Markdown format](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) 
for convenient editing and version control.

The JSNIRF format is built upon the [JData specification](https://github.com/fangq/jdata/) - 
a generalized framework to serialize and convert complex scientific data. 
The JSNIRF specification is compatible with [JData specification Draft 1](https://github.com/fangq/jdata/commit/f8fc8f1b814e7a4654b7b0092de15eaafa94d3da).

## How to participate

You can use a number of methods to provide your feedback to the working 
draft of this file specification, including

- [Create an "Issue"](https://github.com/fangq/jsnirf/issues)
  - This is the most recommended method to provide detailed feedback or 
    discussion. An "Issue" in github is highly versatile. One can ask a 
    question, report a bug, provide a feature request, or simply propose
    general discussions. Please use URLs or keywords to link your discussion 
    to a specific line/section/topic in the document.
- [Write short comments on Request for Comments (RFC) commits](https://github.com/fangq/jsnirf/)
  - A milestone version of the specification will be associated with an
    RFC (Request for comments) commit (where the entire file is removed
    and re-added so that every line appears in such comment). One can
    write short comments as well as post replies on this RFC page. 
  - To add a comment, you need to first register a github account, and then 
    browse the above RFC page. When hovering your cursor over each line, a 
    "plus" icon is displayed, clicking it will allow one to comment on a 
    specific line (or reply to other's comments).
  - The RFC page can get busy if too many comments appear. Please consider 
    using the [Issues section](https://github.com/fangq/jsnirf/issues) if this happens.
  - One can browse the commit history of the specification document. If
    anyone is interested in commenting on a particular updated, you can also
    comment on any of the commit page using the same method.
- [Use the JData mailing list](https://groups.google.com/forum/#!forum/openjdata)
  - You may send your comments to the jdata mailing list (openjdata at googlegroups.com). 
    Subscribers will discuss by emails, and if a motion is reached, proposals
    will be resubmitted as an Issue, and changes to the specification will be
    associated with this issue page.

For anyone who wants to contribute to the writing or revision of this document,
please follow the below steps

- Fork this repository and make updates, then create a pull-request
  - Please first register an account on github, then, browse the 
    [JSNIRF repository](https://github.com/fangq/jsnirf);
    on the top-right of this page, find and click the "Fork" button.
  - once you fork the JSNIRF project to your own repository, you may edit the
    files in your browser directly, or download to your local folder, and 
    edit the files using a text editor;
  - once your revision is complete, please "commit" and "push" it to your forked
    git repository. Then you should create a pull-request against the upstream
    repository (i.e., `fangq/jsnirf`). Please select "Compare cross forks" and 
    select `"fangq/jsnirf"` as "base fork". Please write a descriptive title for
    your pull-request. The project maintainer will review your updates
    and choose to merge to the upstream files or request revision from you.
    
