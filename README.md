# MarkDown语法总结
@[toc]
## 1.标题 
```
# 标题一
## 标题二
### 标题三
#### 标题四
##### 标题五 
###### 标题六

标题一
===
标题二
---
```



## 2. 段落
不加任何修饰符号即为一个段落。

## 3. 强调
（1）*倾斜*（* *）  
（2）**加粗**（ ** ** ）  
（3）***加粗并且倾斜***（*** ***）  
（4）~~删除线~~（~~ ~~）

## 4. 列表 
（1）无序列表
```
星号/加号/减号 + 空格 +列表内容
```
实例：
- html
    - 哈哈
    - 哼哼
- css
- javascript

（2）有序列表
```
数字 + 英文句号 + 空格 + 列表内容
```
实例
1. 哆啦A梦
2. 樱桃小丸子
3. 蜡笔小新

## 5. 链接
```
[链接文字](url地址)
```
（1）外部链接
```
[百度](https://www.baidu.com)
```
[百度](https://www.baidu.com)

(2) 内部链接
```
[demo1](./demo1.md)
```
[demo1](./demo1.md)  


```
目标 {#index}
[列表](#index)
```

[列表](#index)

（3）引用式链接
```
定义：[百度]: https://www.baidu.com
使用： [百度]
```
[百度]

## 6.  图片

```
![alt](utl, title)
```
```
![图片链接](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1566104102358&di=c05b3de005c8de858830a3a6296efa0f&imgtype=0&src=http%3A%2F%2Fwx1.sinaimg.cn%2Flarge%2F7eba71a1gy1g5x0ouira1j20hs0a0wno.jpg 'ggdd')

```
![图片链接](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1566104102358&di=c05b3de005c8de858830a3a6296efa0f&imgtype=0&src=http%3A%2F%2Fwx1.sinaimg.cn%2Flarge%2F7eba71a1gy1g5x0ouira1j20hs0a0wno.jpg 'ggdd')

```
![yuzuru hanyu](./img/timg.jpg 'yuzuru')
```
![yuzuru hanyu](./img/timg.jpg 'yuzuru')





## 7. 引用
```
>锄禾日当午，汗滴禾下土。 
>>>床前明月光
```
>锄禾日当午，汗滴禾下土。 

>>>床前明月光

## 8. 代码
（1）单行 
如 `var a = 1`  那么`console.log(a)`
```
`var a = 1`
`console.log(a)`
```
（2）多行且高亮
```javascript
var a = 1;
console.log(a);
```

## 9. 分割线


分割线一 (---)

---

分割线二 (***)

***

分割线三 (___)

___

## 10. html代码
```
<p style="font-size: 18px; text-align:center">实例</p>
```

<p style="font-size: 24px; text-align:center">实例: p标签</p>

## 11. 表格
```
表格两端|可省
| title1 | title2| title3|
|---| :---: |----:|  左对齐/居中对齐/右对齐
|cell1|cell2|cell3|
|aaaaaaaaa| bbbbbbb | ccccccc|
```
| title1 | title2| title3|
|---| :---: |----:|
|cell1|cell2|cell3|
|aaaaaaaaa| bbbbbbb | ccccccc|
<!-- 注释 -->

## 12. GFM 
（1）tasklist
```
- [x] task1
- [x] task2
- [ ] task3
```
- [x] task1
- [x] task2
- [ ] task3

（2）表情
```
: 单词 :
:sunny:
:dog:
:pig:
:cat:
```
:sunny:
:dog:
:pig:
:cat:






[百度]: https://www.baidu.com
