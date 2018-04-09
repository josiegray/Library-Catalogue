Josie’s Library Catalogue

=========================



The Project

———————————

I started this project because I wanted a digital record of the books that I own. This project will allow me to track books that I own and information about them for quick reference. It will also allow me to easily share information about my books with other people, track the location of my books, and it will act as a backup in case anything ever happens to my books or I am forced to get rid of them at short notice. 

These files are primarily intended for my own use. However, all are welcome to access, share, remix, and revise my work under the terms of the CC BY 4.0 International Licence (See licence information below). 




While this project resembles a library catalogue, I developed my own XML language so I could personalize the information I include for each book. I don't really care about publication dates or number of page numbers, but I do care about where the book is, how many times I've read about it, and personal connections and stories that I may have about a book. 

At this time, there are 125 books included in this list. I plan to add more. I also plan to expand on the information provided for each book to make it more interesting and personal. 

Features

————————


This project contains three files: an .XSD schema, the .XML source file, and a .CSS file. 



The XSD file defines rules for the XML language that I am using. It can be easily edited to add or remove fields. 



The XML file contains a record of all of the books in my personal collection. Each book must have a title and the location (options include Port Edward, Victoria, Lent out, or Unknown). Beyond that, there are a number of optional fields to fill out where applicable. These include a subtitle, a rating (using a scale from 1-5, with "Unread" or "Didn't finish" as options), a summary, notes about the book, the last time I read it, the number of times I have read it, and a list of subject terms. Books that are part of a series are grouped together within a series tag. For many series, I include a rating, notes, and subject list for the whole series, rather than repeating the information for each book.  Books are divided into two categories: Fiction and Non-Fiction. My fiction books are sorted alphabetically by author's last name. My non-fiction books are sorted by subject: Creative Non-Fiction, History, Politics, and Writing. History, Politics, and Writing each have sub-subjects. Within subjects and sub-subjects, books are organized by author's last name. However, in the future I plan to reorganize those books so they are grouped within a subsection by topic. Copyright and licencing information are located at the end of the document within the <closing> tag. 

The CSS file included in this project provides a visibly pleasing option for viewing the books in my collection in a web browser.


 I have used CSS to ensure that all information is labelled and that visual markers clarify what books are grouped together.


To view and edit these files, you will need a text editor or Oxygen software (available for purchase and download at https://www.oxygenxml.com/).

How to View the Library in Your Browser 
————————————————————————
————————————
———
1. Download Josie's Personal Library.xml and Josie's Personal Library.css. 
2. Associate the CSS file with the XML file:
	2a. Paste the file location of the CSS file in the XML file. 
	    (e.g. <?xml-stylesheet type="text/css" href="Final%20stylesheet2.css"?>). 
	2b. Save.
3. Right click on the .xml file and click “Open in browser" (e.g., Firefox, Chrome, Safari, Microsoft Edge). 

Access Files and Contribute
——
——
——
——
——
——
——
——
——————————
—
Source Code: https://github.com/josiegray/Library-Catalogue
Issue Tracker: https://github.com/josiegray/Library-Catalogue/issues

Contact

———————

These files are maintained by Josie Gray. If you have any questions, comments, or issues, you can contact me at josie-g@outlook.com. 

If you plan to share, use, or remix my work, I would love to know.




License

———————

The project copyrighted by Josie Gray (2018) and is licensed under a CC BY 4.0 International Licence (https://creativecommons.org/licenses/by/4.0/). 

If sharing or remixing, or revising this work, please include the following attribution statement with anything you share: "'[File name]' (link to GitHub) by Josie Gray (https://github.com/josiegray) is under a CC BY 4.0 International Licence (https://creativecommons.org/licenses/by/4.0/)."
 

If you have modified my work, please include a description of the changes you made.