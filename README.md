# MAILPiX
Script for GMail live forensics
```
__  __    _    ___ _     ____  _ __  __
|  \/  |  / \  |_ _| |   |  _ \(_)\ \/ /
| |\/| | / _ \  | || |   | |_) | | \  / 
| |  | |/ ___ \ | || |___|  __/| | /  \ 
|_|  |_/_/   \_\___|_____|_|   |_|/_/\_\
				                    
M a i l P i X  - G m a i l   E X T R A C T O R	
```
MAILPiX GMail Extractor - 4 CHROME, FIREFOX, EDGE, OPERA 

Description: A script that extracts throught default gmail interface e-mails records.
Based on the same browser console techniques  described in paper:
Soares, A. (2022). WhatsApp Web Client Live Forensics Technique. In Proceedings of the 8th International Conference on Information Systems Security and Privacy - ICISSP, ISBN 978-989-758-553-1, pages 629-636. DOI: 10.5220/0011006400003120

* Copyright: 2026 Alberto Magno <alberto.magno@gmail.com> 
* URL: https://github.com/kraftdenker/
* Author: alberto.magno@gmail.com (https://github.com/kraftdenker)  

## Description:
A script that extracts mails in eml format (RFC 5322). In line with forensics procedures, the technique extracts digital data that can be loaded into forensic tools for analysis or visualized direct using a mail application.
More details in the article:
<https://medium.com/@alberto.magno/gmail-live4n6-liveforensics-a583d8da8635>

## Usage
* Logged in an gmail account web interface <https://mail.google.com/>
* Enter in browser console (CTRL+I or F12)
* Paste the content of MAILPiX.js into console and press ENTER (its possible to copy it to transferarea direct from github web interface). In Firefox and others, you have to manually type "allow paste"/"allow pasting" into the console to enable pasting.
* An interface will be injected on gmail UI.
* Check the e-mails you want to export and click "ADD CHECKED E-MAILs" button. Then, click "TAKEOUT" to save the extracted data in a ZIP file.You can also clear the export data or show the last calculated digest using the respective buttons.
TIP: You can use the usual search options from gmail interface making a refined search before selecting the e-mails to export. For example, search for "subject:invoice" to list only e-mails with "invoice" in the subject or e-mails after a certain date. Then, select the desired e-mails and proceed with the export.
* Takeout your extraction.

Have a nice 4n6.
