# Cogmaster
Cog manager bot

Plan:
- clone from git repos
- check for cogcfg.json file
- load prefs ans include modules + configs
- possibly use upload from website db

Aim:

Git repositories should host a cogcfg file, as public cogs. Next, if a repo is added it adds the cogs to it as a module. 


How to?:

To setup your respository, simply create a github repository and put in the following file:

*save as `cogcfg.json`*
```json
{
"name": "example",
"version": "1.0",
"author": "Eris9/Kaneki",
"files": ["link1","link2pyfile"],
"modules": ["link1","link2pyfile"],
"exec": "bash to execute eg. echo hi thank you for installing package by me, for more info check https://example.com leave blank for none",
"pyexec": "link to pyfile to be executed leave blank for none"
""
}
```

To be added - upload your repository to a global list.
