AUTO Commit and Auto Push To Github

How To Run ?

on termux :
1. pkg update & upgrade
2. pkg install php
3. pkg install bash

------------------------------------

1. Create a personal Access Token of your github account (https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token) [minimum : repo permission]
2. Open config.php
3. Fill $username = your github username
4. FIll $token with your personal access token
5. php run.php [ manuals ]
6. sh ulg.sh [ it will automatically commit every 24 hours ] [ recommended using vps ]
7. wait until the program end

