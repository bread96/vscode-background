## 배경 이미지 설정

extension -> background -> setting -> Edit in setting.json

```
"background.enabled": true,
  "background.loop": false,
  "background.useDefault": false,
  "background.useFront": true,
  "background.style": {

    "content": "''",
    "pointer-events": "none",
    "position": "absolute",
    "z-index": "99999",
    "width": "100%",
    "height": "100%",
    "background-position": "left",
    "background-size": "cover",
    "background-repeat": "no-repeat",
    "opacity": 0.2
  },
  "background.customImages": [
    "https://user-images.githubusercontent.com/94351468/149452636-babdb444-aae9-4fbb-831d-b3d4a48b7a87.jpg"
  ]
```
