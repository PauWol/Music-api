# Music-api
A Music api that needs a account first for using a token.

## Usage
If you request with `/auth` you can either:
- create an account with
```json
{"name":"yourName" ,"password":"yourPassword"} 
```
or 
- if the account alredy exsists and both password and email are correct you get your token
- if the account doesnt exsists it creates a new one and sends your token, email etc. back.

If you request using `/stream/<yourToken>` you can request by:
- a search
```json
"query":"yourSearch"
```
- or by url
```json
"url":"yourUrlOfVid"
```
This returns a streaming link and other information.
