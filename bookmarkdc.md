# Discord Bookmarklet

Created By viloid (github.com/vsec7)

*** NOTE : USE AT YOUR OWN RISK! ***

## Get Selfbot Discord Token
![GET TOKEN](https://i.ibb.co/zQxbc6M/bookmarklet1.jpg)
```
javascript:(()=>{var t=document.body.appendChild(document.createElement`iframe`).contentWindow.localStorage.token.replace(/["]+/g, '');prompt('Get Selfbot Discord Token by github.com/vsec7', t)})();
```

## Login With Selfbot Discord Token
![LOGIN](https://i.ibb.co/0QTr1Gm/bookmarklet2.jpg)
```
javascript:(()=>{var t=prompt('Login With Discord Token by github.com/vsec7', 'INPUT YOUR TOKEN HERE');document.body.appendChild(document.createElement`iframe`).contentWindow.localStorage.token=`"${t}"`;location.href='/channels/@me'})();
```

# How to Use ?
![CLICK](https://i.ibb.co/ZHSFWHn/click.jpg)

- Open discord.com
- Click Bookmarklet

> Use Selfbot token for [Auto Chat Bot](https://github.com/vsec7/DiscordSelfbot)

> Use for Switch Discord Account Login with same browser

** Dont logout your account, because it can regenerate new token. Just switch with another token **

## • Donate

SOL Address : viloid.sol

BSC Address : 0xd3de361b186cc2Fc0C77764E30103F104a6d6D07
