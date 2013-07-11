Week 1 Tasks
============

Readings for next week
----------------------

1. JavaScript Overview: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/JavaScript_Overview>
2. Values, variables, and literals: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Values,_variables,_and_literals>
3. Expressions and operators: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators>
4. Statements (Control Flow): <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Statements>
5. Functions: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions>


Practice using Git for submitting future assignments
----------------------------------------------------

For additional help, see <https://help.github.com/> and <http://git-scm.com/book>. If you get really stuck, contact the instructor <danmuzyka.ai@gmail.com>.

1. If you have not done so already, install Git on your local machine. See <http://git-scm.com/book/en/Getting-Started-Installing-Git> for help.
2. If you do not yet have a GitHub account, sign up for one at <https://github.com/>. Be sure to enter an SSH key into your GitHub account.
3. Return to this page, and click on the *Fork* button in the top right corner of the page.
4. Click on the dropdown for *branch: master*. 
5. We are going to create a new branch of this repository, which will be named with your first and last name. In the *Find or create a branch...* text box, type your name as one word (for example: danmuzyka). Press enter.
6. Near the bottom right column of the page, find the SSH clone URL, and copy it (git@github.com:aipdx-wdim387/week1.git).
7. Go to the command line on your local machine, and clone the repository from the clone URL:
    git clone git@github.com:aipdx-wdim387/week1.git
8. When the clone process completes, change directory into the repository:
    cd week1
9. Checkout the branch you created. In the example below, replace *danmuzyka* with the name of your branch:
    git checkout --track -b danmuzyka origin/danmuzyka
10. In your favorite editor, create a file named *hello.js*. The file should have the following content:
    console.log("Hello, class!");
11. Save *hello.js* inside your week1 directory.
12. Add this file to Git. From within the week1 directory, type:
    git add hello.js
    git commit -m "Adding hello.js"
13. Push this change back up to GitHub. In the example below, replace *danmuzyka* with the name of your branch:
    git push origin danmuzyka
14. Back on GitHub, look at the page for your forked copy of the respository (for example, https://github.com/danmuzyka/week1/tree/danmuzyka ). Click on the *Compare & pull request* button.
15. Write a brief message in the box provided and click *Send pull request*.

Dan will review the submitted pull requests.
