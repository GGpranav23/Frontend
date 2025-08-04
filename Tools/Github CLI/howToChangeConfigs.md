1. Check the current user name, mail and email using following commands respectively:
    Syntax: "git config --get user.name" or "git config user.name"
    Syntax: "git config --get user.mail" or "git config user.mail"
    Syntax: "git config --get user.email" or "git config user.email" 

2. Modifying the global configs:
    NOTE: **Global configuration: Applied to all repos** 
    Syntax: git config --global user.name "your name"
    Syntax: git config --global user.mail "your mail"
    Syntax: git config --global user.email "your email"

3. Modifying the local configs:
    NOTE: **Global configuration: Applied to current repo only** 
    Syntax: git config user.name "your name"
    Syntax: git config user.mail "your mail"
    Syntax: git config user.email "your email"