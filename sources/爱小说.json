{
    //.网站信息
    "name": "爱小说",
    "url": "www.ixs.cc",
    "version": 100,
    //2.基础信息
    "search": {
        "url": "https://www.ixs.cc/search.htm?keyword=${key}",
        "charset": "utf-8"
    //3.搜索
        "list": "div.left > section.lastest",
        "name": "n2",
        "detail": "n2 > a"
    }
    //4.目录
    "catalog": {
        "list": ".mulu > ul",
        "orderBy": 0,
        "booklet": {
            "name": ".volume@match->(?<=])(.+)(?=共[0-9]+章)",
            "list": "li"
        },
        "name": "a",
        "chapter": "a"
    }
    //5.正文
    "chapter": {
        "content": ".content > br",
        "purify": ["参考"]
    }
}
