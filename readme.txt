HTML

To start creating a webpage, the linux text editor was called from the terminal and a new html editor page was opened. Then the tag <!DOCTYPE html> was used to let the browser know that the file was an html file. Next the <head> was opened to enter the metadata of the file. Then the tag <title> was opened to enter the title of the page and the both tags were closed. Next the <body> tag was opened to display contents in the body of the webpage. First a navigation bar was created using the <nav> tag and the webpages was linked together by the anchor tag. <ul> tag was used to display the link to the anchored pages in the navigation bar in an unordered list. A background image was also added after opening the body tag. The headings in the body was given by the header tags and the image was added using the img tag. Similarly three other html doccuments was created and each of them was linked to one another using the anchor tag.<table> tag was used to create a table and the <th> tag was used to add contents to the table.

GITHUB

To push the files into Github, firstly the folder was opened in the terminal that contained the files that were needed to be pushed into the repository in Github. Then the following command was entered into the terminal to let Git know that the opened folder was to be recognized as a git repository.
git init
Then the command 
git add .
and the command 
git status 
was used to know the status of the files
was ran in the terminal to add files into git. Then the following command 
git commit -m “First web page”
was ran. The command 
git remote add origin https://github.com/harikrsr/Python-Programming-lab.git
git push -u origin master
were used to add files to the master root in the remote repository.
