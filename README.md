#Node E-mal sender

##Description:
This application should send a e-mail every modification in files.

##Get Started:
- Create auth.conf.json put there you e-mail and password, don't worry, it is on gitignore so it won't be send to git
```json
//auth.conf.json
{
   "user": "youremail@gmail.com",
   "pass": "yourpassword"
}
```

- Edit email.conf.json put from who you want to send, the subject and the text
- Run npm run start
- Edit email.conf.json again and another e-mail wil be sent
