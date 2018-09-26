## PreRequisites ##
* Download Git
* Create a GitHub Account

## GitHub ##
1. Create a repo in Github
2. Clone the repo and copy the link
3. Open Git and navigate to your project
4. To Clone type in:
    * Git clone https://github.com/FuryRX/background-generator.git
    * This will copy your Github folder to your local documents folder
    * Now we need to copy the contents of your folder to Github
5. Navigate in CMD to the new folder that has been copied to your local
6. Type in:
    * Git status
    * This shows the status of files comparing to github and local
    * Type in:
      - `Git add html.index`
      - `Git add style.css`
      - `Git add Script.js`
      - `Git status` to see the new status
    * Now we need to commit
      - Type in:
      - `Git commit -m "adding starting project"`
      - `If the above command doesn’t work you may need to type:`
      - `Git config --global user.name "th22@live.co.uk"`
      - `Then type`
      - `Git push`
      - Login with your github account
7. Now remember when you start you need to pull the project down incase of any new code
    * `Git pull`
