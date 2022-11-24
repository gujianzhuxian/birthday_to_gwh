### 来自开源项目“[霸都丶傲天](https://github.com/AJLoveChina/birthday.git)”
## 生日快乐

> <b>修改config.js的配置就可以为您心爱的人做一个超具创意的网页生日快乐呀,喜欢的话可fork/start我的或者"https://github.com/AJLoveChina/birthday.git"</b>


## TODO
* [x] 每行祝福文字可以配一张图片
* [ ] 配图支持旋转

### config.js 说明
> 温馨提示: 每句话丶每个图片地址丶每个按钮文字的那一行，最后都要以**英文逗号**结尾哦！
```text
var config = {
    // 句子的长度可以任意， 你可以写十句话， 二十句话都可以
    // 每句话尽量不要超过15个字,不然展示效果可能不太好
    texts: [
        "送给",      //这里,每句话结尾的最后一个逗号必须是英文的哦!! 很重要哦!!
        "和蔼可亲的学姐",  // 同上...
        "今天是你的生日",
        "❉ 平凡而又珍贵的一天",
        "❉ 前进路上得片刻闲暇",
        "❉ 且听平凡世间，秋冬一步步走来",
		"❉ 且迷这风浪",
		"❉ 永远廿一赶朝暮",
		"❉ 将昨日事归欢喜处",
        "❉ 祝福你生日快乐🎂🎂🎂",
        "❉ 祝福你实现理想！🙂🙂🙂",
        "❉ 祝福你生命中得每一天永远青春靓丽！🙂🙂🙂",
        "OVER~~",
    ],
    /**
     * imgs 可以不填, 但是如果要填写的话必须遵循下面的格式
     * "对应上面的文字, 要完全一样" : "图片地址, 可以把图片放在imgs文件夹中"
     * 例如
     * "和蔼可亲的学姐": "./imgs/gwh.jpg"
     *
     * 如果不要图片的话, 直接在每行开头写两个斜杠注释即可, 例如下面的 "今天是你的生日" 的图片就不会展示了:)
     * Tip: 图片最好用正方形or接近正方形, 看起来效果更好
     */
    imgs: {
        "和蔼可亲的学姐": "./imgs/gwhxiaokeai.png",
        // "今天是你的生日": "./imgs/birthday.jpg",
    },
    // 按钮文字描述, 以下是默认的按钮文字，英文的，您可以改成你喜欢的文字
    desc: {
        turn_on: "开始",
        play: "音乐",
        bannar_coming: "颜色",
        balloons_flying: "好像少点东西",
        cake_fadein: "蛋糕？",
        light_candle: "蜡烛？",
        wish_message: "生日快乐",
        story: "A MESSAGE FOR YOU",
    }
};
```


## 截图演示
<img src="./assets/birthday-demo2.gif"/>

## 知乎使用教程
[https://zhuanlan.zhihu.com/p/85899661](https://zhuanlan.zhihu.com/p/85899661)

## 结尾
网页模板,简历模板,知识笔记,PDF书籍,原创深度技术分享等 :heart:
我的：
* Github:[gujianzhuxian](https://github.com/gujianzhuxian/birthday_to_gwh.git)\
* 原开源项目：
** 知乎:[霸都丶傲天](https://www.zhihu.com/people/AJLoveChina)
** Github:[霸都丶傲天](https://github.com/ajlovechina)
