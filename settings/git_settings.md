Git & GitHub & GitHubPage Settings
================================

## [Git Install & Settings](http://git-scm.com/)
- [install git](http://git-scm.com/download/linux)
- [global config](http://git-scm.com/book/ja/Git-%E3%81%AE%E3%82%AB%E3%82%B9%E3%82%BF%E3%83%9E%E3%82%A4%E3%82%BA-Git-%E3%81%AE%E8%A8%AD%E5%AE%9A)
    - git config --global user.email "__MailAddress__"
    - git config --global user.name "__UserName__"
    - git config --global color.ui auto
    
## [GitHub](https://github.com)
- [sign up](https://github.com/)
    - username
    - email address
    - password
    - confirm
- Create Remote Repository
    - sign in https://github.com/
    - Create New repository
        - repository name
        - check initialize
    - Create gh-pages branch
        - in branch text box Type gh-pages
    - setting -> default -> gh-pages
- Wait about 10 minites 
- Clone Repository
    - $git clone https://github.com/ __username__ / __repositoryname__
    - $cd __repository__
    - $echo "test" > index.html
    - $git add index.html
    - $git commit -a -m "add index.html"
    - $git push -u origin gh-pages
