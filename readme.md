# [CzechFuture.tech web](https://czechfuture.tech/)

## Requirements
- Node.js v8 or above
- Firebase tools ([read more](https://firebase.google.com/docs/cli))   

## Instalation 

### Step 1 - Run app locally
```
firebase serve
```
Start's local server (usually at URL http://localhost:5000/) with app.

### Step 2 - Deploy app to server
```
firebase deploy
```
It can call only users with access to [Firebase `czech-future-tech` project](https://console.firebase.google.com/project/czech-future-tech).

Currently is deploy produced automactically by Travis CI. Just delivery new content do `master` branch on GitHub repository.
