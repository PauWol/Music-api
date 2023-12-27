# Music-api
a Music api that needs a account first for using a token

if you request with /auth you can egther create a account with "name":"yourName" ,"password":"yourPassword" or if the account alredy exsists and both passwords and email are correct you get your token if the account doesnt exsists it creates a new and sends your token and email etc. back.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
if you request with /stream/<yourToken> you can request by a search "query":"yourSearch" or by url "url":"yourUrlOfVid" and then you get a streaming link and other information back.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
