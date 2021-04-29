## Different pages
### About [(```index.php```)](https://enos.itcollege.ee/~issoys/cv-assistant/index.php)
General page that would explain the webpage.
Used scripts:
- [```main.php```](main.php)
- [```functions.js```](functions.js)

### FAQ [(```faq.php```)](https://enos.itcollege.ee/~issoys/cv-assistant/faq.php)
As it name says a Frequent Answered Questions page.
Used scripts:
- [```main.php```](main.php)
- [```functions.js```](functions.js)

### Login [(```login.php```)](https://enos.itcollege.ee/~issoys/cv-assistant/login.php)
Login page that handles the users login and redirects to the main page with a different navigation menu. Logout is handled with script [```logout.php```](logout.php)
Used scripts:
- [```main.php```](main.php)
- [```handlelogin.php```](handlelogin.php)

### Create account [(```create.php```)](https://enos.itcollege.ee/~fortin/cv-assistant/create.php)
Page for creating an account. It validates the input username and password and then tries to add it to the DB. If the username already exists it will give an error and in the site is promted a message.
Used scripts:
- [```main.php```](main.php)
- [```adduser.php```](adduser.php)
- [```functions.js```](functions.js)

### Edit CV [(```edit.php```)](https://enos.itcollege.ee/~issoys/cv-assistant/edit.php)
A page to edit the active user CV. The form is handle in the script [```main.php```](```main.php```). The addition buttons will be handled later with JS.
Used scripts:
- [```main.php```](main.php)
- [```onlylogged.php```](onlylogged.php)
- [```editform.php```](editform.php)
- [```functions.js```](functions.js)

### Feedback [(```feedback.php```)](feedback.php)
A page where the user can give feedback to work collegues as well as request feedback from collegues for him/herself.
Used scripts:
- [```main.php```](main.php)
- [```onlylogged.php```](onlylogged.php)
- [```recommend.php```](recommend.php)
- [```functions.js```](functions.js)
