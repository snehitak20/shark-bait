# shark-bait

## Description

The goal of this project is to ultimately have a webpage that is optimized for search engines, and whose codebase will meet accessibility standards. The codebase follows semantic HTML elements, has accessible alt attributes, and has a descriptive title. The codebase will also have sequential heading attributes, and follow a logical structure. 

For this project, the main objective was to refactor the code so that it would follow HTML semantics and proper code semantics. It should also maintain its current appearance despite any changes that were made to refactor the code. As such, the webiste title was renamed to a more descriptive title that is indicative of the webpage. Tags such as `<section>, <article>, <footer>, <header>` were used to replace `<div>` tags, and helped to create a logical and semantic structure. For images, accessible alt attributes were written. Heading attributes were confirmed to be in sequential order. In the style.css file, comments were written to indicate the various CSS selectors and their functions that were used for this project. 

![CSS screenshot with CSS file comments](.assets/images/CSS-snapshot.jpg)
![HTML screenshots with the different tag changes](.assets/images/HTML-screenshot.jpg)

[Link to webpage](https://snehitak20.github.io/shark-bait/)

## Installation

To complete a project like this, follow these steps. 

1. Create a new repository on Github. 
    - Press the "+" sign on the top right hand corner, or the "new" button on your GitHub homepage. 
    - Create an unique name for your repository, and make the respository public. 
    - Click the "README" option to include the "README" page. 
    - Your new repository has been created.
2. Open GitBash (PC users) or Terminal (Mac users).
    - Navigate to where you want to clone your new repository onto your local machine. 
        - Use `cd` to help you navigate. 
3. To clone the new repository onto your local machine. 
    - Click the respository that you just made on github.com.
    - Click the "code" button and choose the SSH option. 
    - Copy the SSH option to your clipboard. 
    - On GitBash/Terminal, enter the command `git clone git@github.com:<UserNAME>/<demo-repo>.git`
        - After `git clone`, paste the SSH option from your clipboard into GitBash/Terminal.
        - Since the SSH option was used, enter the password for the SSH key when asked. 
4. You have now cloned your new repository.
    - Using `cd`, navigate into your new repository from the location that you have saved it in. 
    - Use `ls` to see what is inside the new repository currently. 
        - It should only include the README page as of now.
5. Tranferring the project files into your new directory on your local machine. 
    - Using Finder/Explorer, copy the corresponding files that are needed to edit your project. 
    - In another Finder/Explorer window, navigate to your new repository, and paste the files directly into that folder. 
6. On GitBash/Terminal, after pasting the project files into the new repository. 
    - Use `ls` to see what is now inside the new repository.
        - This should now include the README page, and the project files that you have copy-pasted in. 
7. Use `git status` to see if there any changes that need to be made to the repository. 
    - At this point, git will tell you that there is an untracked file .
8. Use `git add .` to add the new project files, and allow the new files to be tracked by git.
9. Use `git commit -m "add base project files"` to commit the changes have recently been made to the repository. 
10. Use `git push origin main` to sync your local machine with GitHub. 
    - Enter your SSH password when prompted. 
11. Use `code .` to open the files on a code reader of your choice.
12. Edit the files as necessary in your code reader. 
13. Periodically, and when you are finished with editing your code: 
    - Follow Steps 7-10 to keep your repository up to date with the changes that have been made. 
14. You have successfully completed this project!

## Usage

To navigate this webpage, click one of the links in the navigation bar that will lead you to the appropriate area of the website.

## Credits

The original code was given by UC Berkeley Extension, Coding Bootcamp.

## Reflection

For this project, it was important to learn what HTML semantics are. Additionally, it was important to know what webpage accessibility standarda are. To create a logical structure in the HTML file, it was important to know which HTML semantics were most appropriate to us. This project stands out because it follows the requirements that are needed for an accessible webpage.

## License

Licensed under the [MIT](https://choosealicense.com/licenses/mit/) license. 