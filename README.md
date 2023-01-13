# katsuShareX
## selfHost setting up
all you need to do is just "Cloning This repo." by using
```zsh
git clone https://github.com/dethMastery/katsuShareX.git
```

and then setting up password in `app.js`
<br />

## ShareX setting up
all you need for ShareX setting up is just copy this config and feel free to using shareX

```json
{
  "Version": "14.1.0",
  "Name": "katsuCDN",
  "DestinationType": "ImageUploader",
  "RequestMethod": "POST",
  "RequestURL": "https://img.katsuragi.cyou/api/upload",
  "Headers": {
    "password": "aKatsu198"
  },
  "Body": "MultipartFormData",
  "FileFormName": "image",
  "URL": "{json:URL}"
}
```