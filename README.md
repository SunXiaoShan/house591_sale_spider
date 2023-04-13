# 591 中古屋爬蟲 #

### 用途 ###
這是一個 591 中古屋網頁的爬蟲, Python 寫的。

---

### Install ###
```
pip install requests
pip install beautifulsoup4
```

---

### 資料結構 ###
```
{
    "type": "2",
    "houseid": 132xxxx850,
    "kind": 9,
    "kind_name": "住宅",
    "shape_name": "透天厝",
    "region_name": "台中市",
    "section_name": "西屯區",
    "title": "xxxxx買臨路店住透天住三用地",
    "has_carport": 0,
    "room": "3房2廳2衛",
    "floor": "1F~2F/2F",
    "photoNum": "15",
    "mainarea": 23.21,
    "carttype": " ",
    "cartmodel": "平面式",
    "is_video": 0,
    "is_full": 0,
    "photo_url": "https://xxxx.jpg!400x300.jpg",
    "refreshtime": "6天前",
    "nick_name": "仲介XXXX",
    "housetype": 3,
    "isnew": 0,
    "posttime": 168xxx039,
    "area": 23.21,
    "houseage": 49,
    "showhouseage": "49年",
    "address": "中xxxxxx巷",
    "browsenum": 260,
    "unit_price": "xxxx.77萬/坪",
    "unitprice": "xxxxx.77",
    "price": 1xxx0,
    "showprice": "1,xxx",
    "is_oversea": "0",
    "is_carport": "0",
    "is_down_price": 0,
    "is_combine": 2,
    "isvip": 0,
    "is_hurry_price": 0,
    "community_link": " ",
    "community_name": " ",
    "tag":
    [
        "有陽台"
    ],
    "saletype": 0,
    "delivery": " ",
    "fci_pai": " ",
    "pc_good_house": 0,
    "good_house": 0,
    "mvip": 0,
    "m_recom": 0,
    "user_id": 24xxxx70
}
```

---

### Reference ###
https://blog.jiatool.com/posts/house591_spider
https://github.com/it-jia/house591_spider
https://github.com/vance0725/591_sale/blob/master/sale.js
