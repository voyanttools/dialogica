# Managing Corpora using Spreadsheets or XML: Teaching Guide

**Note**: This page is a **teaching guide** with advice for using [Walkthrough 4: Managing Corpora using Spreadsheets or XML](https://drive.google.com/drive/u/0/folders/1a2VRBO_vULjZ7t5t2DA8wMN0hQNC18zw) (Downloadable MS Word file). 

**Also**: Our general teaching philosophy is available in the [Introduction](/intro.md). Feel free to skip this Teaching Guide and just read and adapt the Walkthrough. It is shared under a [Creative Commons By Attribution license](https://creativecommons.org/licenses/by/4.0/) so you can do what you want.

## Aboout Walkthrough 4

The fourth walkthrough is designed to show students how to manage a corpus of short texts using either a spreadsheet or XML. You will probably want to teach either one or the other, but not both. Delete what you don't need. 

### Objectives

To get students to the point they can:

- Understand the difference between a single text and corpus
  - Understand why one would want to develop a corpus
- Understand how to use a spreadsheet to manage a corpus
- Understand how to use XML to manage a corpus
- Understand how to upload and use a corpus in Voyant

## Discussion

This walkthrough is designed to show students how they can use text analysis to study all sorts of things other than literary works. It 

### Spreadsheets

- You can have students use either Google Sheets or Excel for this. We've tested both.
- Spreadsheets become unmanageable if you load too many cells with lots of text. A spreadsheet works well for about 100 web pages. 
- Make sure you show them how to paste a lengthy text into a single cell rather than having each line go into a different cell! It is also useful to show them how to manipulate the width of columns and height of rows.
- It is useful to have students document the texts they are gathering in a spreadsheet even if they keep the full text separatly in text files.

### XML

- If you are going to teach students to use XML you need to take some time to explain XML to them. W3Schools has an [XML Introduction](https://www.w3schools.com/xml/xml_whatis.asp) (and there are lots of other introductions out there.)
- You need to be careful as to what editor you suggest students use. They may use Microsoft and think that it saves XML (wich is does, but not the way they think.) It is useful to mention that in Word they have to remember to save a text file. At the high end, you can have students download the 30-day trial version of [oXygen](https://www.oxygenxml.com/). This is a complex tool that may distract them from text analysis. Only use oXygen if you want them to learn about XML in depth anyway.
- The minimal XML you need to introduce so that they can use XML to manage a corpus would include:
  - Explain that they need a single root element like <corpus>
  - Explain elements and attributes and provide them a simple model.
  - Explain that they need to check if the XML is well-formed and how they can do that just by dragging the file to Chrome. 
  - Explain some of the common typos to look for like special characters in the text (<, &), unclosed elements, different spelling of element names, and so on.

## How to teach with this walkthrough
Here is an outline for how you might teach this as a module in a larger course. This assumes that you have already introduced text analysis using the earlier walkthroughs like [E-Texts and Analysis](/extexts.md). 

1. Introduce the module and emphasize the objectives.
  1. Explain what a corpus is and why one would want to use a corpus. 
  1. Encourage students to think about iteratively building and studying a corpus. Talk about how they can add interpretative metadata as their research progresses.
  1. Talk about how a corpus can be developed to study all sorts of phenomena, not just literature. Give examples.
1. Show a small project where you gathered a small number of web pages on a subject and documented it in a spreadsheet or XML.
  1. Show students and example of how you copied and pasted text into the spreadsheet or XML file and added the metadata.
  1. Show how to upload to Voyant so that documents are recognized. You can also show how one could create groups for comparison either by saving subtexts from a spreadsheet or using the Group by feature in the XML upload options.
1. Assign an exercise where students have to build a small corpus and document it. The idea is that the students then go through a version of Walkthrough 4 that you have edited to include your exercise and the technology (spreadsheets or XML)that you want them to use.
  1. The assignment will create the context for them to use the edited Walkthrough 4.
  1. Organize a help session so that students who get stuck can share their screens and get help. The help might be peer-to-peer or something you provide.
  1. You should specify how you want the assignment returned. One approach is to ask for one page of documentation and a copy of the file (spreadsheet or XML file.) This focuses on creating the corpus and can be followed by an assignment that focuses on studying the corpus.
1. After you have seen the assignments you can have a closing lecture/discussion to reinforce the ideas and give students ideas about where they could go with this.

----

[Dialogica Home](/index.md) | [Previous: Sharing Results](/share.md) | 

----

&copy; Stéfan Sinclair & Geoffrey Rockwell

All materials on this site shared under a [Creative Commons By Attribution license](https://creativecommons.org/licenses/by/4.0/).
