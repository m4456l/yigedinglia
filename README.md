# 一个顶俩
寻找成语接龙终点（一切归于一个顶俩）

包括娘要嫁人、凑手不及的话，实际上最后合格的仅有“一个顶俩” “救过不给”两个

也可以说按QQ红包的标准，新华字典中只有这两个成语可以终结一场成语接龙

main2.cpp  生成output.txt（UTF-8格式）请与jsoncpp一起编译
main.cpp   遍历output.txt（UTF-8格式）来获取不可接龙的音 请与Pinyin.h一起编译
idiom.json 成语数据库，可自行替换

字典数据来源于https://github.com/pwxcoo/chinese-xinhua 使用jsoncpp读取
拼音获取引用了：https://github.com/wzhe/GetPinyin 提供的类
