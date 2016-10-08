#Opencart: Author's email field for multiseller(multimerch)

##Intro
Hola! Amigos.. It been a while since i last release an Extension. Am sorry i don't have an excuse. 

####Issue
 I want a situation where as an admin, i can manage seller's activities (product: Author email to be specific) on my site, to some extend i can but, something is still lacking.. which was how to contact buyer regarding a particlar product information. e.g. a book store (author's Email)

Well this extension resolved the issue listed above.

###Prerequisite
- Must have Opencart installed on your system. 
- Must be running a multistore App.
- Must have VQmod installed.

###Usage 
 - Download the extension
 - Unzip it.
 - You can upload via FTP, Cpanel and or OCMOD installer (I prefer using FTP..its faster and straight forward).
 - Remember to be carefull not to Overwrite any file. 

####Create new column in the DB table
Use this code to create a new column in your DB.
ALTER TABLE `product`
    ADD COLUMN `authors email` INT(10) AFTER `model`;

###Extra Features
- Enable email field in the admin section.
- Re-arrange Product from "Aphabetical order" to "Dated_at".
