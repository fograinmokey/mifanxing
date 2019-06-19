## 推荐
### 获取推荐列表 /recommended

+ Description
    + [must] header.X-User-ssid 会话标识 例：9a4b8dcf-1234-1234-1234-505e73621f59
    + [must] cookie.X_U_SSID 会话标识 例：9a4b8dcf-1234-1234-1234-505e73621f59
    + [must] 用户登录后需要附带登录标记
    
+ Parameters
    + filter[shown] 是否展示过，【必填】，示例：filter[shown]=false|true
    + filter[firstRecTime] 打开推荐页面的时间，【非必填】，当filter[shown]=true时，【该参数必填】，格式比须按照[yyyy-MM-dd hh:mm:ss]填写，示例：filter[firstRecTime]=2019-03-27 15:27:39
    + page[number] 页码，【非必填】，不填时默认为1，当filter[shown]=false时，【该参数必须为1或不填】
    + page[size] 页长，【非必填】，不填时默认为10

+ Response 200 (application/json)

        {
            "meta": {
                "totalPages": 1,
                "totalElements": 8,
                "size": 10,
                "number": 1,
                "numberOfElements": 8,
                "first": true,
                "last": true,
                "sort": null
            },
            "links": {
                "self": "/topics/search?page[number]=1&page[size]=10",
                "first": "/topics/search?page[number]=1&page[size]=10",
                "last": "/topics/search?page[number]=1&page[size]=10"
            },
            "data": [
                {
                    "id": "1602207",
                    "meta": {
                        "score": 0.20977913
                    },
                    "forumId": 3,
                    "forumName": "新闻",
                    "topicType": 0,
                    "topicTypeValue": "正常",
                    "imageSingle": false,
                    "imageRotation": false,
                    "creator": 0,
                    "created": "2019-03-22 17:00:00",
                    "modified": "2019-03-24 21:37:37",
                    "wx": 1,
                    "wxTopicId": 132584,
                    "articleTopicId": 1602207,
                    "reviews": 0,
                    "replies": 0,
                    "thumbsUp": 0,
                    "thumbsDown": 0,
                    "thumbs": 0,
                    "liked": 0,
                    "favorite": 0,
                    "brand": null,
                    "rotations": null,
                    "images": [
                        {
                            "filename": "//static.mifanxing.com/wx/image/238/15/1044168.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/238/15/1044169.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/238/15/1044170.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/238/15/1044171.jpg"
                        }
                    ],
                    "coverImages": null,
                    "from": {
                        "image": "//static.mifanxing.com/iyyren/image/201808/27/1317/377531032376852480.jpg",
                        "fetchReviews": 213,
                        "reviews": 213,
                        "wxSeedId": 227,
                        "seedId": 373,
                        "origin": "http://mp.weixin.qq.com/s?__biz=MzAxNzUxMTg4NA==&mid=2649596718&idx=1&sn=ce0d37a5f95947ea26bc1474b234cd9f&chksm=83fd678db48aee9b677b8e4b006193d42d5d28d1e34c82ddca34c9363791f11ace0380b6dfcc&scene=27#wechat_redirect&seedId=227&groupSign=1553325544110&top=1&original=100&articletime=1553245200",
                        "host": "null://null",
                        "rating": null,
                        "source": "SHOWVEN孝文科技",
                        "fetchThumbsUp": 1,
                        "channelId": 366
                    },
                    "wxCategoryId": 4,
                    "post": {
                        "postType": 1,
                        "postTypeValue": "爬取",
                        "title": "SONICBOOM PLUS | 音爆王双管速喷气柱",
                        "description": "音爆王双管速喷气柱 SHOWVEN 最新研发，高端速喷气柱--SONICBOOM PLUS音爆王双管速喷气柱。采用创新独特双管输出设计，响应速度快，出烟量极大，安全性高，携带方便，安装灵活，适宜于各类大型舞台演出、酒吧夜店、新品发布会等活动，效果震撼！ 配置38颗9W LED灯珠，能显著增亮气柱，提..."
                    },
                    "document": {
                        "postDate": "2019-03-22",
                        "author": "SHOWVEN孝文科技",
                        "documentType": 1,
                        "original": 0
                    },
                    "similarities": []
                },
                {
                    "id": "1602253",
                    "meta": {
                        "score": 0.19294451
                    },
                    "forumId": 3,
                    "forumName": "新闻",
                    "topicType": 0,
                    "topicTypeValue": "正常",
                    "imageSingle": false,
                    "imageRotation": false,
                    "creator": 0,
                    "created": "2019-03-23 19:19:41",
                    "modified": "2019-03-26 11:31:35",
                    "wx": 1,
                    "wxTopicId": 132613,
                    "articleTopicId": 1602253,
                    "reviews": 5,
                    "replies": 0,
                    "thumbsUp": 0,
                    "thumbsDown": 0,
                    "thumbs": 0,
                    "liked": 0,
                    "favorite": 0,
                    "brand": null,
                    "rotations": null,
                    "images": [
                        {
                            "filename": "//static.mifanxing.com/wx/image/239/15/1044466.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/239/15/1044467.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/239/15/1044469.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/239/15/1044470.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/239/15/1044471.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/239/15/1044472.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/239/15/1044473.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/239/15/1044474.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/239/15/1044475.jpg"
                        },
                        {
                            "filename": "//static.mifanxing.com/wx/image/239/15/1044476.jpg"
                        }
                    ],
                    "coverImages": null,
                    "from": {
                        "image": "//static.mifanxing.com/iyyren/image/201802/03/1621/303287728718626816.jpg",
                        "fetchReviews": 503,
                        "reviews": 503,
                        "wxSeedId": 8,
                        "seedId": 132,
                        "origin": "http://mp.weixin.qq.com/s?__biz=MzA5MDU2NjA4MA==&mid=2651881838&idx=2&sn=77425d7fae7da5b427b1c044f27a1670&chksm=8bed9dc1bc9a14d702e7f47db460e031bb808c3e4be36d95160d4d6849f5399c2bfe401a49b8&scene=27#wechat_redirect&seedId=8&groupSign=1553341007851&top=0&original=11&articletime=1553339981",
                        "host": "null://null",
                        "rating": null,
                        "source": "Eplay吉他",
                        "fetchThumbsUp": 6,
                        "channelId": 118
                    },
                    "wxCategoryId": 4,
                    "post": {
                        "postType": 1,
                        "postTypeValue": "爬取",
                        "title": "《春、来了》吉他指弹视频 和春天有一个约会...",
                        "description": "春为岁首，万物萌新 春是一年的开始，是希望的开始 是一切美好的开始 常言道：一年之计在于春、一日之计在于晨 春作为二十四节气中的第一个节气 立春和立夏、立秋、立冬一样 反映着四季的交换 也意味着新的轮回已再度开启 最寒冷的冬季过去时、春天降临 天气开始逐渐变暖，万物渐次复苏 春天最是适合旅游的时候 ..."
                    },
                    "document": {
                        "postDate": "2019-03-23",
                        "author": "Eplay吉他",
                        "documentType": 1,
                        "original": 1
                    },
                    "similarities": []
                }
            ]
        }

### 获取未展示的推荐文章个数 /recommended/notShowSize

+ Description
    + [must] header.X-User-ssid 会话标识 例：9a4b8dcf-1234-1234-1234-505e73621f59
    + [must] cookie.X_U_SSID 会话标识 例：9a4b8dcf-1234-1234-1234-505e73621f59
    + [must] 用户登录后需要附带登录标记

+ Response 200 (application/json)       
     
        {
            "data": 20
        }

### 主动触发推荐任务 /recommended/satrtRecommending
+ Description
    + [must] header.X-User-ssid 会话标识 例：9a4b8dcf-1234-1234-1234-505e73621f59
    + [must] cookie.X_U_SSID 会话标识 例：9a4b8dcf-1234-1234-1234-505e73621f59
    + 用户登录后需要保存登录信息
+ Response 200 (application/json)


## 分类
### 查询类别详情[GET] /admin/Classifications/{id}

+ Parameters
     +  id 类别id

+ Response 200 (Application/json)

      {
        "data": {
            "id": 2,
            "parentId": 1,
            "classificationName": "行业新闻",
            "parent": {
                "id": 1,
                "parentId": 0,
                "classificationName": "资讯"
            }
        }
      }

### 查询类别列表[GET] /admin/Classifications

+ Description 
     + filter[parentId]=0（参数固定值；获取所有的父节点）
     + filter[parentId]=1（参数非固定值；获取某个父节点下的子数据）
     + page[number]=1&page[size]=10
     + sort -modified(从新到旧) | modified(从旧到新)

+ Response 200 (Application/json) (获取所有的父节点示例)

      {
        "meta": {
            "totalPages": 1,
            "totalElements": 1,
            "size": 10,
            "number": 1,
            "numberOfElements": 1,
            "first": true,
            "last": true,
            "sort": null
        },
        "links": {
            "self": "/admin/Classifications?filter[parentId]=0&page[number]=1&page[size]=10",
            "first": "/admin/Classifications?filter[parentId]=0&page[number]=1&page[size]=10",
            "last": "/admin/Classifications?filter[parentId]=0&page[number]=1&page[size]=10"
        },
        "data": [
            {
                "id": 1,
                "enabled": 1,
                "creator": 0,
                "modifier": 0,
                "parentId": 0,
                "classificationName": "资讯",
                "displayorder": 0
            }
        ]
     }

+ Response 200 (Application/json) (获取某个父节点下的子数据)

      {
        "meta": {
            "totalPages": 1,
            "totalElements": 9,
            "size": 10,
            "number": 1,
            "numberOfElements": 9,
            "first": true,
            "last": true,
            "sort": null
        },
        "links": {
            "self": "/admin/Classifications?filter[parentId]=1&page[number]=1&page[size]=10",
            "first": "/admin/Classifications?filter[parentId]=1&page[number]=1&page[size]=10",
            "last": "/admin/Classifications?filter[parentId]=1&page[number]=1&page[size]=10"
        },
        "data": [
            {
                "id": 2,
                "enabled": 1,
                "creator": 0,
                "modifier": 0,
                "parentId": 1,
                "classificationName": "行业新闻",
                "displayorder": 0
            },
            {
                "id": 3,
                "enabled": 1,
                "creator": 0,
                "modifier": 0,
                "modified": "2019-06-05 18:25:14",
                "parentId": 1,
                "classificationName": "设备/乐器",
                "displayorder": 0
            },
            {
                "id": 4,
                "enabled": 1,
                "creator": 0,
                "modifier": 0,
                "modified": "2019-06-05 18:25:40",
                "parentId": 1,
                "classificationName": "录音/混音",
                "displayorder": 0
            },
            {
                "id": 5,
                "enabled": 1,
                "creator": 0,
                "modifier": 0,
                "parentId": 1,
                "classificationName": "作曲/编曲",
                "displayorder": 0
            },
            {
                "id": 6,
                "enabled": 1,
                "creator": 0,
                "modifier": 0,
                "parentId": 1,
                "classificationName": "舞台/扩声",
                "displayorder": 0
            },
            {
                "id": 7,
                "enabled": 1,
                "creator": 0,
                "modifier": 0,
                "parentId": 1,
                "classificationName": "声音设计",
                "displayorder": 0
            },
            {
                "id": 8,
                "enabled": 1,
                "creator": 0,
                "modifier": 0,
                "parentId": 1,
                "classificationName": "音源/插件",
                "displayorder": 0
            },
            {
                "id": 9,
                "enabled": 1,
                "creator": 0,
                "modifier": 0,
                "parentId": 1,
                "classificationName": "声学装修",
                "displayorder": 0
            },
            {
                "id": 10,
                "enabled": 1,
                "creator": 0,
                "modifier": 0,
                "parentId": 1,
                "classificationName": "周边/其他",
                "displayorder": 0
            }
        ]
      }

### 更新文章类别标识[PUTCH] /admin/Topics{id}?classificationId={classificationId}
+ Description
    + [MUST] authenticated
    + [MUST] ROLE_ADMIN
+ Description 
    + id - 更新的文章ID
    + classificationId - 分类ID

+ Response 200 (Application/json)
  
      {
       "data": 1
      }  
    
