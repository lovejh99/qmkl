# /users/favorite 接口
---

#### 说明
收藏列表接口

#### 请求
```
GET    /users/favorite HTTP/1.1  收藏列表
```

#### 是否需要登录
```
是
```

#### 参数：
```
|参数|类型|是否必需|说明|示例|
```

#### 响应
```
HTTP/1.1 200 OK
```
```
{
  "containerType": "favorite_list",
  "containerTitle": null,
  "callback": null,
  "actionUrl": null,
  "actionText": null,
  "data": [
    {
      "container_type": "recording",
      "recording": {
        "id": "6755399282198688",
        "media_type": "audio",
        "media_url": "http://zhaohailei.box.ushow.media/api/v17/ios/sm/en/phone/2x/recordings/6755399282198688/masterhls",
        "star_clip_url": null,
        "is_public": false,
        "cover_image": "https://d2odow79s717pv.cloudfront.net/production/songs/cover_img/ca7197f40e28e00bd01c497b849c02c2.jpg",
        "small_cover_image": null,
        "publish_time": 1488880432,
        "recording_desc": "",
        "song_id": "5370501695537152",
        "user_id": "6755399373947282",
        "views": "0",
        "likes": "1",
        "has_liked": false,
        "web_url": "https://m-test.starmakerstudios.com/share/?recording_id=6755399282198688",
        "masterhls": "#EXTM3U\n#EXT-X-VERSION:3\n#EXT-X-ALLOW-CACHE:YES\n#EXT-X-TARGETDURATION:11\n#EXT-X-MEDIA-SEQUENCE:0\n#EXTINF:10.007800,\nhttps://d2odow79s717pv.cloudfront.net/test/transcoding/recordings/6755399282198688/hls-audio/seg00000.ts\n#EXTINF:6.524811,\nhttps://d2odow79s717pv.cloudfront.net/test/transcoding/recordings/6755399282198688/hls-audio/seg00001.ts\n#EXT-X-ENDLIST\n\n",
        "favorited_at": "1489117248"
      },
      "song": {
        "id": "5370501695537152",
        "artist": "Shawn Mendes",
        "title": "Treat You Better",
        "total_time": 182,
        "token_price": 0,
        "is_vip": false,
        "cover_image": "https://d2odow79s717pv.cloudfront.net/production/songs/cover_img/ca7197f40e28e00bd01c497b849c02c2.jpg",
        "sing_count": 0,
        "lyric_url": "https://d2odow79s717pv.cloudfront.net/production/lyrics/ba98aa547061da8e5605fca1f2338faf?Expires=1489806794&Signature=Xbqrgmnio1RpI7PQEHCnPNed2hCboPLHYwJrWz7Y8umlhobpEbKoQvivnDdVCgHGuB0VXnvBaXySjYAXrJXhiscns5xEs7eYVVA9Llasc51XvtyGy-5Rw2wFLapZzL90GwZnhRK8qURdRQZfdgVIX34EeuksNIlp9iQzQPPXUjncAc9jz8up9VMgQYCkLuwWEk-EojRnl7Inur1B1D7R7OuzJYXzQIPWI2M~ZnuEtWeEqhhp-xZrhsSVaO4Tk6PS2WPLtziYvrjkpSLmQofxKa3YAQPmzea-a1zXKusdUPVWtanoYiWQveGEdYg~oBQCLt4i4LeMPULusaZVZypNWg__&Key-Pair-Id=APKAJOTAAFZOJZWNWKZA",
        "instrumental": "https://d2odow79s717pv.cloudfront.net/production/songs/instrumental/7fd50f27780a51f8f3445f53d0c7a883.m4a?Expires=1489768130&Signature=O30I9SkOBfhq7W6RaE1PiyJHMr2puMxIGeItMSmQ1x8JmGV~aAd-U1gbcsC8NF2rZTt-YVKa7xtG-4KAcReU4k6qYJ0PW~OkAxUXQ6FNUm7PoSkYgHHEww9x-knhQwhb2gPjzRmB6BzzZWQ2FF5dJ2-H8JFr0cAQJeuxLsIPbEgMVNiZCqxhscTKeea~9TLfbr1oxuC6wgWpREOhR-w-hqDuJ1JX6ApWxaWyU4ts3n9PaS-WXqiTSa5K3SqHWliWgmJNpMDa2QF3HEZxRg-hjWyYsn-WXci~RJiJB05z4OfcF7rHG-i~aXSZ0~dC6Kvm4y3yYd~NDK~00TdH~lSBXg__&Key-Pair-Id=APKAJOTAAFZOJZWNWKZA",
        "song_key": "C#",
        "description": "",
        "hook_start": 34000,
        "hook_end": 59000,
        "copyright": true,
        "song_quality": 0,
        "hd": false
      },
      "user": {
        "id": "6755399373947282",
        "stage_name": "qq460839552",
        "profile_image": "https://scontent.xx.fbcdn.net/v/t1.0-1/p200x200/14457373_107219656408081_944213302461534332_n.jpg?oh=41a2ea18cf88ddff0b42bb49a7990fc5&oe=5925FF36",
        "is_vip": true
      }
    },
    {
      "container_type": "recording",
      "recording": {
        "id": "6755399282198686",
        "media_type": "video_native",
        "media_url": "http://zhaohailei.box.ushow.media/api/v17/ios/sm/en/phone/2x/recordings/6755399282198686/masterhls",
        "star_clip_url": null,
        "is_public": true,
        "cover_image": "https://d2odow79s717pv.cloudfront.net/test/uploading/recordings/6755399282198686/cover_image.png",
        "small_cover_image": "https://d2odow79s717pv.cloudfront.net/test/uploading/recordings/6755399282198686/cover_image-thumbnail.png",
        "publish_time": 1488876228,
        "recording_desc": "",
        "song_id": "6137769508470784",
        "user_id": "6755399373947282",
        "views": "0",
        "likes": "0",
        "has_liked": false,
        "web_url": "https://m-test.starmakerstudios.com/share/?recording_id=6755399282198686",
        "masterhls": "#EXTM3U\n#EXT-X-STREAM-INF:PROGRAM-ID=1,BANDWIDTH=539648,RESOLUTION=360x360,CODECS=\"avc1.42001e,mp4a.40.2\"\nhttps://d2odow79s717pv.cloudfront.net/test/transcoding/recordings/6755399282198686/hls-low/playlist.m3u8\n#EXT-X-STREAM-INF:PROGRAM-ID=1,BANDWIDTH=923648,RESOLUTION=360x360,CODECS=\"avc1.42001e,mp4a.40.2\"\nhttps://d2odow79s717pv.cloudfront.net/test/transcoding/recordings/6755399282198686/hls-high/playlist.m3u8\n\n",
        "video_available": true,
        "favorited_at": "1489116608"
      },
      "song": {
        "id": "6137769508470784",
        "artist": "Taylor Swift",
        "title": "You Belong With Me",
        "total_time": 224,
        "token_price": 200,
        "is_vip": false,
        "cover_image": "https://d2odow79s717pv.cloudfront.net/production/songs/cover_img/42051f794542a5ae8e6c9c3f6afac709.jpg",
        "sing_count": 0,
        "lyric_url": "https://d2odow79s717pv.cloudfront.net/production/lyrics/0a19c4d7c9adc1d8ab8eac1fcd377c2f?Expires=1489933531&Signature=mZNfE0irSNaJJ5cttmmKAXH1RCdsJVeaIQQn5BAmDvy-TfWkzmOQSxXLxeekPFkGjmYeIwNko-zKEOdrc4YBgNPZqEw6PK57dgcXWCgkI0c1eWTRnW5sWe3JVi9T9~-gKnocLPOtmYpyo3FKtRJgV7MN3TynCVsCLqxUfx6S6gvhPZ73sUOFpZFFzMmWgFy7HcKR5KSCgdNKQOEi9CQAUyVq1R4~Z-LTGPZGvU4tIuOG4JBBZScnZ0n4nR~4j2WFIos4jNtuGKy~-CEaGtRWaDxPCGEaaw-QOPvf8dyc9lk0lUjJESi4~cVxfvTkCNiJt75~KmIQ08FRvfn9Z9AnvA__&Key-Pair-Id=APKAJOTAAFZOJZWNWKZA",
        "instrumental": "https://d2odow79s717pv.cloudfront.net/production/songs/instrumental/6a7aeb21c8512128e487dfc04ee76100.m4a?Expires=1490212853&Signature=O5M0P0gkPc7dL8H0MVQ-IZA7PYN8zSbf0SXmdzeWUvFkMjZ41Q-OSz2oXtjE6fvUu70bHiMVClondciwYJ2oz4zoM8zF2P5jsjKLnBD9ej-dhUQghvrFnuBGOpEVFYR-eswPsH8ah08B9tamrjpoG6AGRu1-oVWwZ-lUswXVSYJzmf~~Zp0FxfflL0EKhAEcLubOMvVDwcvs8ldY~57MreFxGoDSVl93J5EdCwcVd8nl~tBAnX6kRA8BPhXx98UcBR2zn-mg8oGn5BvVk4eO-qNaVwpSC228BAIgbGVnCJC~C0Ld3j7BLIGg2SniLZAL9fKI5SAXA9yy5VMmlfySXw__&Key-Pair-Id=APKAJOTAAFZOJZWNWKZA",
        "song_key": "F#",
        "description": "",
        "hook_start": 51000,
        "hook_end": 66000,
        "copyright": true,
        "song_quality": 0,
        "hd": false
      },
      "user": {
        "id": "6755399373947282",
        "stage_name": "qq460839552",
        "profile_image": "https://scontent.xx.fbcdn.net/v/t1.0-1/p200x200/14457373_107219656408081_944213302461534332_n.jpg?oh=41a2ea18cf88ddff0b42bb49a7990fc5&oe=5925FF36",
        "is_vip": true
      }
    },
    {
      "container_type": "recording",
      "recording": {
        "id": "6755399282198694",
        "media_type": "audio",
        "media_url": "http://zhaohailei.box.ushow.media/api/v17/ios/sm/en/phone/2x/recordings/6755399282198694/masterhls",
        "star_clip_url": null,
        "is_public": true,
        "cover_image": "https://d2odow79s717pv.cloudfront.net/production/songs/cover_img/ac7f297b1883040a7cb06cb218175481.jpg",
        "small_cover_image": null,
        "publish_time": 1489048390,
        "recording_desc": "",
        "song_id": "4577326704099328",
        "user_id": "6745494332899328",
        "views": "3",
        "likes": "0",
        "has_liked": false,
        "web_url": "https://m-test.starmakerstudios.com/share/?recording_id=6755399282198694",
        "masterhls": "#EXTM3U\n#EXT-X-VERSION:3\n#EXT-X-ALLOW-CACHE:YES\n#EXT-X-TARGETDURATION:11\n#EXT-X-MEDIA-SEQUENCE:0\n#EXTINF:10.005333,\nhttps://d2odow79s717pv.cloudfront.net/test/transcoding/recordings/6755399282198694/hls-audio/seg00000.ts\n#EXTINF:10.005333,\nhttps://d2odow79s717pv.cloudfront.net/test/transcoding/recordings/6755399282198694/hls-audio/seg00001.ts\n#EXTINF:5.653333,\nhttps://d2odow79s717pv.cloudfront.net/test/transcoding/recordings/6755399282198694/hls-audio/seg00002.ts\n#EXT-X-ENDLIST\n\n",
        "favorited_at": "1489116187"
      },
      "song": {
        "id": "4577326704099328",
        "artist": "Backstreet Boys",
        "title": "I Want It That Way",
        "total_time": 212,
        "token_price": 200,
        "is_vip": false,
        "cover_image": "https://d2odow79s717pv.cloudfront.net/production/songs/cover_img/ac7f297b1883040a7cb06cb218175481.jpg",
        "sing_count": 0,
        "lyric_url": "https://d2odow79s717pv.cloudfront.net/production/lyrics/a2c549a87d05598d1a425b4cd5724c84?Expires=1490211337&Signature=O3clvgTLqnhndx~5ODwMlxg8Ehqu8Jd9bdvHHEiN1qdBM~-ctCE1br1fkDrBJy4eREnWH-6i2W7r~DcrupSfuJbaDQMeE04JkbCkJrivvv1syeuis5qkJXP-6nzqEB58Mz08VHCNBLT7LW4ZWIzByia1ZwzJ4YZLtdjgS~VuFonFk7w-zRkAvGuY4FQ01chDprZTGFdj0a0qlZcW--WlvRN0z3Y9qJAiFWRWnlxhY4WvJG0HHgBdByeVwYSBC1mIuzUAdYajYBqjnEkntMYmnlSEyiMHcl0~a6Ek--B79hykWryXqLccME1YRUOrCYQDlcds5DZznrB0a4PKyU9itg__&Key-Pair-Id=APKAJOTAAFZOJZWNWKZA",
        "instrumental": "https://d2odow79s717pv.cloudfront.net/production/songs/instrumental/adbacf1c4490654ecbbb99dee45ae80c.m4a?Expires=1489832698&Signature=kfHeZ1oNgB5ZwGTivlLgkTgsY3Sw0bsoolymfeVLybYm8VS72dmomWfpg-P~5k3WZAEn34WYIkxSbvfXzDtiB0v234NCa7wkRBBFRhyMiqyKflHloyakVKvSj7w7ABi7SB~NBALHdXKJmPyPymhJ2X7G2QisNsCprMbtNqXUYSSww7YBM1ERT9b6qMOOrX9EV8OBd6gp6Oejnz8leNdo2WZvXI4FldPKP3kJ0W-UQEMXWdzU9Eb~~PgXYOIDBYlTx7d-aZuCbea95UKqga0yOxp2dcEJDcfYPnKiNUL6W-eNQ7zykHG5G9DaUlienSe2Mm3k6fwyin56cWzq2RVCPg__&Key-Pair-Id=APKAJOTAAFZOJZWNWKZA",
        "song_key": "A",
        "description": "",
        "hook_start": 86000,
        "hook_end": 107000,
        "copyright": true,
        "song_quality": 0,
        "hd": false
      },
      "user": {
        "id": "6745494332899328",
        "stage_name": "feiwang",
        "profile_image": "https://scontent.xx.fbcdn.net/v/t1.0-1/p200x200/14993472_1301034379939107_7517311106746301575_n.jpg?oh=8d2ffa344de0b553d6494d5544de2192&oe=5967CF99",
        "is_vip": true
      }
    }
  ]
}
```
