Credits: https://github.com/megadose/toutatis

## 💡 Prerequisite
[Python 3](https://www.python.org/downloads/release/python-370/)

## 🛠️ Installation
### With PyPI

```pip install toutatis```

### With Github

```bash
git clone https://github.com/megadose/toutatis.git
cd toutatis/
python3 setup.py install
```


### If Errors occur:

```bash
pip install urllib3==1.26.15
pip install six
```


## 📚 Usage:

### Find information from a username

```
toutatis -u username -s instagramsessionid
```

### Find information from an Instagram ID

```
toutatis -i instagramID -s instagramsessionid
```

## 📈 Example

```
Informations about     : xxxusernamexxx
Full Name              : xxxusernamesxx | userID : 123456789
Verified               : False | Is buisness Account : False
Is private Account     : False
Follower               : xxx | Following : xxx
Number of posts        : x
Number of tag in posts : x
External url           : http://example.com
IGTV posts             : x
Biography              : example biography
Public Email           : public@example.com
Public Phone           : +00 0 00 00 00 00
Obfuscated email       : me********s@examplemail.com
Obfuscated phone       : +00 0xx xxx xx 00
------------------------
Profile Picture        : https://scontent-X-X.cdninstagram.com/
```

## 📚 To retrieve the sessionID
1. Open Instagram, right click and select 'Inspect'
2. Open the Tab 'Application'
3. Click 'Cookies' in the left column and select 'https://www.instagram.com'
4. Copy the Value of 'sessionid'
![](https://files.catbox.moe/1rfi6j.png)

## Thank you to :

- [megadose](https://github.com/megadose)
- [EyupErgin](https://github.com/eyupergin)
- [yazeed44](https://github.com/yazeed44)
