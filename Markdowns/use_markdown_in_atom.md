# Use Markdown in Atom
>install a plugin for markdown
[markdown-preview-enhanced](https://shd101wyy.github.io/markdown-preview-enhanced/#/zh-cn/installation)
[GitHub Flavor Markdown](https://help.github.com/articles/basic-writing-and-formatting-syntax/)
**To open preview**
> Ctrl+Shift+M

## Code
### Single line
`int main(argc[], argv[][])`
### Code block
```C
for(int i=1;i<n;i++)
    {
      if(i>10)
        break;
    }
```
## 字体
----
**这是加粗的文字**
*这是倾斜的文字*

***这是斜体加粗的文字***

~~这是加删除线的文字~~

## Unordered list
- 1
- 2
  - next
    - next
- 3

## Ordered list
1. first
2. second
  1. list 2.1
    1. list 2.1.1

## To do list
- [x] havedone
  - [x] havedone
- [ ] need to do

## Refer
> first
>>second

> multilines
second
add two space then enter

## Links
[Google](http://www.google.com)
## Insert Pictures
[![Frontpage_of_HITSZ](/assets/Frontpage_of_HITSZ.png)](http://www.hitsz.edu.cn/article/view/id-43440.html)
![HIT_logo](../pic/HIT_logo.jpg)
![HIT_logo](/assets/HIT_logo.jpg)
<img src = ../pic/HIT_logo.jpg width = 30% height = 25% align = center />  <img src = ../pic/HIT_logo.jpg width = 30% height = 25% align = right />


## Table
| Item | quantities | value |
| :--- | ---------:|:----:|
| computer| 5 | $4999.0|

## Graphs
```mermaid
graph TD
  A[square] --> B(round);
  B --> C;
  C --> A;
```

```flow
st=>start: Start:>


```


## Mathematical Formula
Inline formula: $\sum_{i=0}^N\int_{a}^{b}g(t,i)\text{d}t$
