# SSH-Key-Gen
# ساخت و کار با کلیدهای SSH در لینوکس


###### Video : لینک ویدیو یوتیوب
```

```

###### خرید سرور از دیجیتال اوشن :
```
https://m.do.co/c/0fb522deafa4
```
###### خرید سرور از سایت ایرانی : 
```
https://dashboard.azaronline.com/order/?aff=790&p=vps
```
###### خرید دامنه از نیم چیپ: 
```
https://namecheap.pxf.io/BX7m6W
```
###### خرید دامنه سایت ایرانی: 
```
https://dashboard.azaronline.com/order/?aff=790&p=domain
```



**If you think this project is helpful to you, you may wish to give a** 🌟

**Feel Free To Donation:** ❤️

>TRC20: ```TGTyqv2MH7dZztMvaP5PKuS9Bma8RY5Pk8```

>ETH: ```0x5b5202a54e5ce4fb25f0d886254eeb07bb088614```

#### Generate SSH key on Win or Linux:
```
ssh-keygen
```

#### View SSH key on Win:
```
C:\Users\Your-Username\.ssh\id_rsa.pub
```

#### View SSH key on Linux:
```
cd .ssh/
```
#### Then use the Cat command
```
cat id_rsa.pub
```

#### Copy the pub-key and add it to your other server as authorize:

#### Add SSH key to server:
```
nano .ssh/authorized_keys
```

#### Copy SSH key from one server to another:
```
scp id_rsa.pub root@IP:/root/.ssh
scp id_rsa root@IP:/root/.ssh
```
