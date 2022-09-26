# Template_Python
Template

____________________________________________________________________________________________________________

Issue and Pull Request templates:
Git Configuration:
To add an Issue template to a repository create a file called ISSUE_TEMPLATE in the root directory. A file extension is optional, but Markdown files (.md) are supported. Markdown support makes it easy to add things like headings, links, @-mentions, and task lists to your templates.

Pull Request templates follows the same pattern: add a file called PULL_REQUEST_TEMPLATE to the root directory of your repository.

If you’re worried about the added clutter in the root directory of your project, we also added support for a .github/ folder. You can put CONTRIBUTING.md, ISSUE_TEMPLATE.md, and PULL_REQUEST_TEMPLATE.md files in .github/ and everything will work as expected.

https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files

https://github.com/github/gitignore


https://github.com/devspace/awesome-github-templates 

https://github.blog/2016-02-17-issue-and-pull-request-templates/ 

https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions 

____________________________________________________________________________________________________________

Gitignore Global USAGE:
Git Configuration
To tell Git to use the template file (globally, not just in the current repo), I used the following command:
git config --global core.excludesfile ~/.gitignore_global


https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files 

https://github.com/github/gitignore 

____________________________________________________________________________________________________________

Commit Template USAGE:
Git Configuration
To tell Git to use the template file (globally, not just in the current repo), I used the following command:
git config --global commit.template ~/.gitmessage


https://gist.github.com/lisawolderiksen/a7b99d94c92c6671181611be1641c733 

https://gist.github.com/median-man/3a7c4324005e96f02691f3a20aeac26b 

____________________________________________________________________________________________________________
Set-up Pycharm:

How to change settings/default settings:

https://www.jetbrains.com/help/pycharm/configuring-project-and-ide-settings.html 

https://www.jetbrains.com/help/pycharm/setting-up-your-project.html 

https://www.jetbrains.com/help/idea/configuring-project-and-ide-settings.html 

____________________________________________________________________________________________________________
