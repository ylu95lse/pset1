
# MY472 - Data for Data Scientists

## Assignment 0
---

The goal of this first problem set is to make sure you know how to work with GitHub Classroom in order to access, complete, and submit assignments. You will not be evaluated on problem sets.

**Deadline:** Submission not required

---

1. Get started with GitHub

    *  This is your personal "fork" (i.e. copy) of the repository that we provided to you and you can edit it as much as you want.
    
    *  When you finish your work here and commit and push all the changes, we will be able to access them and give you comments. If you get stuck with your assignment, you can commit and push your code at any time and we can provide feedback to your work.
  
2. Create a local clone

    *  Your "fork" lives on GitHub, but you can "clone" a local copy on your personal computer. This is generally what you want to do when you write computer code. After making adjustments locally on your machine, you can commit and push all the changes back to GitHub.
    
    *  Now "clone" the repository using the buttons found to the right side of your browser window as you view this repository (green "__Code__" button).  Use the button labelled "Clone in Desktop", and create a (local) copy on your local drive.
    
        You could also have done this from a terminal window on your local machine using (the URL is from the green "Code" button)
        
        ```bash
        git clone https://github.com/lse-my472/problem-set-1-[your user name]
        ```
        
        or you can do this directly in __RStudio__: 
        
        ```
        File -> New Project... -> Version Control -> Git -> Repository URL: [paste the URL] -> [Create Project]
        ```
  
    *  Go to your local clone and open `information.md` (you can use RStudio or any text editor). Fill in your information.
    
    *  Save the file locally. We now have to stage, commit and push the changed file to your own (forked) version of the repository on GitHub.
    
         If you open GitHub Desktop, you should see the changes there. Add a comment, click "Commit" and "Push"
         
         If you work in RStudio, find "Git" in your upper-right pane. The file "information.md" should occur there. Tick "staged", click "Commit" (add a comment) and push with the green up-arrow.
         
    *  You can check whether it worked by opening GitHub in your browser and visiting your repository. The file `information.md` should now contain your information. (Sometimes it takes a few seconds to upload.)
  
3. Practice the GitHub workflow.

    *  Go to your local repository and find `RMarkdown-practice.Rmd`.
    
    *  There is an error in the script. Fix it!
    
    *  Knit the file to `.html`.
    
    *  Stage, commit, and push the fixed `.Rmd` and the new `.html` to your repository. (Check if all worked via browser.)    

Congratulations, you are finished!

---

4.  OPTIONAL: Create a personal web page.

    *  GitHub offers a possibility to host your personal website for free.

    *  Clone a website repository, modify it, and publish a personal webpage.  You can follow the steps described in:

    Jim McGlone, "[Creating and Hosting a Personal Site on GitHub:
     A step-by-step beginner's guide to creating a personal website and blog using Jekyll and hosting it for free using GitHub Pages.](http://jmcglone.com/guides/github-pages/)".
