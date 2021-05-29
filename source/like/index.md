---
title: 喜欢的
lk: /like
date: 2021-02-04 09:37:10
---

嘤嘤嘤，这里是我所喜欢的~

使用随机排序，排序不分先后w

## 喜欢的人
<link rel="stylesheet" id="kratos-css" href="/css/kratosr.min.css" type="text/css" media="all">

<div class="linkpage"><ul id="likeList"></ul></div>

<script type="text/javascript">
{
    const myLike = [
        ["https://zh.moegirl.org.cn/%E9%B9%BF%E4%B9%83", "https://liliakai-pic.vercel.app/like/sing_kano.webp", "鹿乃", "日本(虚拟?)女歌手"],
        ["https://zh.moegirl.org.cn/%E9%B9%BF%E4%B9%83(%E8%99%9A%E6%8B%9FUP%E4%B8%BB)", "https://liliakai-pic.vercel.app/like/vtuber_ano.webp", "鹿乃（虚拟主播）", "Vtuber组合花寄女子寮的三年级生"],
        ["https://zh.moegirl.org.cn/%E5%87%91%E9%98%BF%E5%BA%93%E5%A8%85", "https://liliakai-pic.vercel.app/like/akua.webp", "湊あくあ", "hololive二期生<!--hololive你给老子滚(ノ｀Д)ノ-->"],
    ];


    let friendNodes = '';
    while (myLike.length > 0) {
        const rndNum = Math.floor(Math.random()*myLike.length);
        friendNodes += `<li><a target="_blank" href="${myLike[rndNum][0]}"><img src="${myLike[rndNum][1]}"><h4>${myLike[rndNum][2]}</h4><p>${myLike[rndNum][3]}</p></a></li>`;
        myLike.splice(rndNum, 1);
    }
    document.getElementById("likeList").innerHTML = friendNodes;
}
</script>


## 喜欢的歌

<div class="linkpage"><ul id="likeList2"></ul></div>

<script type="text/javascript">
{
    const myLike = [
        ["https://c.y.qq.com/base/fcgi-bin/u?__=InR6j", "https://liliakai-pic.vercel.app/like/xiaolu.webp", "ハロ/ハワユ", "「ばんび〜の」专辑内的歌曲"],
        ["https://c.y.qq.com/base/fcgi-bin/u?__=ZCbO4p", "https://liliakai-pic.vercel.app/like/shuanlu.webp", "アイロニ", "「曖昧ばんび～な」专辑内的歌曲"],
        ["https://c.y.qq.com/base/fcgi-bin/u?__=7tM14F", "https://liliakai-pic.vercel.app/like/merry.webp", "メリーメリー (álbum ver)", "「或る街の白昼夢」专辑中的歌曲"],
        ["https://c.y.qq.com/base/fcgi-bin/u?__=Yoo7WX", "https://liliakai-pic.vercel.app/like/Stella-rium.webp" , "Stella-rium", "「Stella-rium」专辑中的歌曲"],
        ["https://c.y.qq.com/base/fcgi-bin/u?__=7ZuQJR", "https://liliakai-pic.vercel.app/like/rye.webp" , "想像フォレスト", "「rye」专辑中的歌曲"],
        ["https://www.bilibili.com/video/BV1x7411H7yA", "https://liliakai-pic.vercel.app/like/yuanfen.webp", "午前0時の無力な神様" ,"「yuanfen」专辑中的歌曲"],
        ["https://c.y.qq.com/base/fcgi-bin/u?__=mcgbDn9", "https://liliakai-pic.vercel.app/like/yuanfen.webp", "罰と罰" ,"「yuanfen」专辑中的歌曲"],
        ["https://c.y.qq.com/base/fcgi-bin/u?__=Jw4cand", "https://liliakai-pic.vercel.app/like/yuanfen.webp", "エンディングノート" ,"「yuanfen」专辑中的歌曲"],
        ["https://c.y.qq.com/base/fcgi-bin/u?__=a1pcwfp", "https://liliakai-pic.vercel.app/like/to_samfree.webp", "マインドボイス", "「いつかの約束を君に」专辑中的歌曲"],
        ["https://c.y.qq.com/base/fcgi-bin/u?__=bn6TUfZ", "https://liliakai-pic.vercel.app/like/to_samfree.webp", "瞬きの星団", "「いつかの約束を君に」专辑中的歌曲"],
        ["https://music.163.com/#/song?id=528116472", "https://liliakai-pic.vercel.app/like/in_osu!.webp" , "Chandelier - King" ,"纯音乐（？）"],
        ["https://music.163.com/song?id=31654455", "https://liliakai-pic.vercel.app/like/victory.webp", "Victory", "第一首喜欢的纯音乐"]
    ];


    let friendNodes = '';
    while (myLike.length > 0) {
        const rndNum = Math.floor(Math.random()*myLike.length);
        friendNodes += `<li><a target="_blank" href="${myLike[rndNum][0]}"><img src="${myLike[rndNum][1]}"><h4>${myLike[rndNum][2]}</h4><p>${myLike[rndNum][3]}</p></a></li>`;
        myLike.splice(rndNum, 1);
    }
    document.getElementById("likeList2").innerHTML = friendNodes;
}
</script>