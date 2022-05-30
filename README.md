# Overview
Each folder is a single story from the Story Teller series, using a Read Aloud EPUB format. It contains SMIL meta data to synchronise the audio with each each page of the book. I have only tested this with Apple Books.

# Instructions
Use ecancrusher, https://www.docdataflow.com/ecancrusher/, to create the compressed epub files that you can drop into Apple Books. Just drag the EPUB folder and drop on the ecancrusher app icon.

# Technical
I have added author, illustrator and narrator data for each book. I don't know the dates for each publication, so just set it to Jan 1982 for now.

I used this tutorial as the basis for the creation of these EPUB projects.
https://www.albertopettarin.it/blog/2014/08/02/how-to-create-epub-3-read-aloud-ebooks.html

I used Calibre, https://calibre-ebook.com, to author the books and Audacity to export the audio labels to create the SMIL data, https://www.audacityteam.org. I added the Audacity exported labels to each EPUB folder.

For practicality, I've chosen to split the audio per page. A later effort could look to provide finer granuality, for a better experience, to allow selection of columns or sections as the resume point.

Right now I'm doing this by hand, but I may eventually look to build some templating scripts to help semi automate some of this.

# Help
Help is please needed. 
- Please review the EPUBs and let me know if there are mistakes. Incorrect images, TOCs and Nav. Issues or improvements with audio synchronisation points.
- Submit new EPUB books. I'll keep trying to do this, but it takes time :(

I'm new to EPUB so if there any experts out there, please let me know how I can improve this. 

# License
All images and audio files in each of the EPUB folders is the copyright material of Eagle Moss - https://en-gb.eaglemoss.com.
Those images and audio files may not be distributed in any form, derived or whole, without the express permission of Eagle Moss. I have contacted Eagle Moss to request permission for inclusion in this Open Source project.

The remaining metadata, to create the EPUBs, is available under Creative Commons Zero.
https://creativecommons.org/share-your-work/public-domain/cc0/

# Links
https://storytellerwebsite.wordpress.com
https://storytellerme.bandcamp.com/releases
