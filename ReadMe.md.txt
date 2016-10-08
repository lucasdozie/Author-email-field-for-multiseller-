Author's email field for multiseller(multimerch)

Description
Hola! once again it been a while since i last release an Extension. Am sorry i don't have an excuse. 

Issue
 - I want a situation where as an admin, i can manage seller's activities (product: Author email to be specific) on my site, to some extend i can but, something is still lacking.. which was how to contact buyer regarding a particlar product. e.g. a book store (author's Email)

Well this extension resolved the issue listed above.

Perequisite
- Must have Opencart installed on your system. 
- Must be running a multistore Web App.
- Must have VQmod install on Web app.

Usage 
 - Download the extension
 - Unzip it.
 - You can upload via FTP, Cpanel and or OCMOD installer (I prefer using FTP..its faster and straight forward).
 - Remember to be carefull not to Overwrite any file. 

Use this code the create a new column in your DB.
paste inside inside your Phpmyadmin.
ALTER TABLE `product`
    ADD COLUMN `authors email` INT(10) AFTER `model`;

Extra Featured
- Enable an email field in the admin section.
- Re-arrange Product from "Aphabetical order" to "Dated_at".