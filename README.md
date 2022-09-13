#  驾照考试题库
## 数据目录
```
├─data
│  └─question
│      ├─1
│      │  ├─a1
│      │  │  └─1-a1-image
│      │  ├─a2
│      │  │  └─1-a2-image
│      │  ├─b1
│      │  │  └─1-b1-image
│      │  ├─b2
│      │  │  └─1-b2-image
│      │  ├─c1
│      │  │  └─1-c1-image
│      │  └─c2
│      │      └─1-c2-image
│      └─4
│          └─4
│              └─4-4-image
```

 ## 获取数据

 我想获取`C1`的`科目1`题库

 题库文件在 `data/question/1/c1/1-c1.json`

 对应的图片在 `data/question/1/c1/1-c1-image/` 图片的名字与问题的`id`一致

##  answer字段对应答案
```
{
	"reason":"查询成功",
	"result":{
		"1":"A或者正确",
		"2":"B或者错误",
		"3":"C",
		"4":"D",
		"7":"AB",
		"8":"AC",
		"9":"AD",
		"10":"BC",
		"11":"BD",
		"12":"CD",
		"13":"ABC",
		"14":"ABD",
		"15":"ACD",
		"16":"BCD",
		"17":"ABCD"
	},
	"error_code":0
}
```
 # 数据来源

以上数据全部由 **[聚合数据](https://www.juhe.cn/)** `驾照题库`提供