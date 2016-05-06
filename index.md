
### ǰ��
>������ʦ��TronClass�����ܹ������㴴�����������ʽ�ḻ�Ŀγ̣����һ������һʱ���˽���õĽ�ѧЧ��������ѧ��ѧϰ·��������ʹ�÷�ʽ�ǳ�������ɣ�����Ը����Լ�������Ӧ���ڿ�ǰ�����кͿκ󣬽����������ݽ��������ȫ���˽�TronClass

>����ѧ����TronClass��һ���ǳ���Ȥ��ѧϰ����ƽ̨���㼴��Ҫѧϰ�Ŀγ̿����ɺܶ���Ȥ�Ķ�����ɣ���������Ƶ������������ҳ�������������������еĿγ�ѧϰ����ҵ�Լ����ԣ����������Ҵ��㿴��TronClass������

###1.	�γ̼���ѧ�����
####1.1	�����γ̼��γ����ͽ���
#####1.1.1	����½��γ̣�����ʦ��ݣ�

- ������ҵĿγ̡�> ������½��γ̡�
- ��������Ա������Ҳ������Ϊ��ʦ�Ľ�ɫ�������ڿ�
- ֧��ToC��Table of Contents����Emoji���顢Task lists��@���ӵ�Markdown��չ�﷨��
- ֧��TeX��ѧ��ʽ������KaTeX��������ͼ Flowchart �� ʱ��ͼ Sequence Diagram;
- ֧��ʶ��ͽ���HTML��ǩ������֧���Զ�����˱�ǩ���������пɿ��İ�ȫ�Ժͼ������޵���չ�ԣ�
- ֧�� AMD / CMD ģ�黯���أ�֧�� Require.js & Sea.js��������֧���Զ�����չ�����
- �����������������IE8+����Zepto.js����֧��iPad��ƽ���豸��
- ֧���Զ���������ʽ��

# Editor.md

![](https://pandao.github.io/editor.md/images/logos/editormd-logo-180x180.png)

![](https://img.shields.io/github/stars/pandao/editor.md.svg) ![](https://img.shields.io/github/forks/pandao/editor.md.svg) ![](https://img.shields.io/github/tag/pandao/editor.md.svg) ![](https://img.shields.io/github/release/pandao/editor.md.svg) ![](https://img.shields.io/github/issues/pandao/editor.md.svg) ![](https://img.shields.io/bower/v/editor.md.svg)

**Ŀ¼ (Table of Contents)**

[TOCM]

[TOC]

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
# Heading 1 link [Heading link](https://github.com/pandao/editor.md "Heading link")
## Heading 2 link [Heading link](https://github.com/pandao/editor.md "Heading link")
### Heading 3 link [Heading link](https://github.com/pandao/editor.md "Heading link")
#### Heading 4 link [Heading link](https://github.com/pandao/editor.md "Heading link") Heading link [Heading link](https://github.com/pandao/editor.md "Heading link")
##### Heading 5 link [Heading link](https://github.com/pandao/editor.md "Heading link")
###### Heading 6 link [Heading link](https://github.com/pandao/editor.md "Heading link")

#### ���⣨�õ��ߵ���ʽ��Heading (underline)

This is an H1
=============

This is an H2
-------------

### �ַ�Ч���ͺ��ߵ�
                
----

~~ɾ����~~ <s>ɾ���ߣ�����ʶ��HTML��ǩʱ��</s>
*б����*      _б����_
**����**  __����__
***��б��*** ___��б��___

�ϱ꣺X<sub>2</sub>���±꣺O<sup>2</sup>

**��д(ͬHTML��abbr��ǩ)**

> �������ĵ��ʻ�������д��ʽ��ǰ���ǿ���ʶ��HTML��ǩʱ����Ĭ�Ͽ���

The <abbr title="Hyper Text Markup Language">HTML</abbr> specification is maintained by the <abbr title="World Wide Web Consortium">W3C</abbr>.

### ���� Blockquotes

> �����ı� Blockquotes

���õ����ڻ�� Blockquotes
                    
> ���ã������Ҫ����հ׻���`��<br />��ǩ`���ڲ��봦�ȼ����������ϵĿո�Ȼ��س����ɣ�[��ͨ����](http://localhost/)��

### ê�������� Links

[��ͨ����](http://localhost/)

[��ͨ���Ӵ�����](http://localhost/ "��ͨ���Ӵ�����")

ֱ�����ӣ�<https://github.com>

[ê������][anchor-id] 

[anchor-id]: http://www.this-anchor-link.com/

GFM a-tail link @pandao

> @pandao

### �����Դ������ Codes

#### ���ڴ��� Inline code

ִ�����`npm install marked`

#### �������

�������ĸ��ո�Ҳ��Ϊʵ������`<pre>`Ԥ��ʽ���ı�(Preformatted Text)�Ĺ��ܡ�

    <?php
        echo "Hello world!";
    ?>
    
Ԥ��ʽ���ı���

    | First Header  | Second Header |
    | ------------- | ------------- |
    | Content Cell  | Content Cell  |
    | Content Cell  | Content Cell  |

#### JS���롡

```javascript
function test(){
	console.log("Hello world!");
}
 
(function(){
    var box = function(){
        return box.fn.init();
    };

    box.prototype = box.fn = {
        init : function(){
            console.log('box.init()');

			return this;
        },

		add : function(str){
			alert("add", str);

			return this;
		},

		remove : function(str){
			alert("remove", str);

			return this;
		}
    };
    
    box.fn.init.prototype = box.fn;
    
    window.box =box;
})();

var testBox = box();
testBox.add("jQuery").remove("jQuery");
```

#### HTML���� HTML codes

```html
<!DOCTYPE html>
<html>
    <head>
        <mate charest="utf-8" />
        <title>Hello world!</title>
    </head>
    <body>
        <h1>Hello world!</h1>
    </body>
</html>
```

### ͼƬ Images

Image:

![](https://pandao.github.io/editor.md/examples/images/4.jpg)

> Follow your heart.

![](https://pandao.github.io/editor.md/examples/images/8.jpg)

> ͼΪ�����Ű׳�ɳ̲

ͼƬ������ (Image + Link)��

[![](https://pandao.github.io/editor.md/examples/images/7.jpg)](https://pandao.github.io/editor.md/examples/images/7.jpg "�����ר������ˮ���꡷����")

> ͼΪ�������ר������ˮ���꡷����
                
----

### �б� Lists

#### �����б����ţ�Unordered Lists (-)
                
- �б�һ
- �б��
- �б���
     
#### �����б��Ǻţ�Unordered Lists (*)

* �б�һ
* �б��
* �б���

#### �����б��Ӻź�Ƕ�ף�Unordered Lists (+)
                
+ �б�һ
+ �б��
    + �б��-1
    + �б��-2
    + �б��-3
+ �б���
    * �б�һ
    * �б��
    * �б���

#### �����б� Ordered Lists (-)
                
1. ��һ��
2. �ڶ���
3. ������

#### GFM task list

- [x] GFM task list 1
- [x] GFM task list 2
- [ ] GFM task list 3
    - [ ] GFM task list 3-1
    - [ ] GFM task list 3-2
    - [ ] GFM task list 3-3
- [ ] GFM task list 4
    - [ ] GFM task list 4-1
    - [ ] GFM task list 4-2
                
----
                    
### ���Ʊ�� Tables

| ��Ŀ        | �۸�   |  ����  |
| --------   | -----:  | :----:  |
| �����      | $1600   |   5     |
| �ֻ�        |   $12   |   12   |
| ����        |    $1    |  234  |
                    
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell 

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

| Function name | Description                    |
| ------------- | ------------------------------ |
| `help()`      | Display the help window.       |
| `destroy()`   | **Destroy your computer!**     |

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

| Item      | Value |
| --------- | -----:|
| Computer  | $1600 |
| Phone     |   $12 |
| Pipe      |    $1 |
                
----

#### ������� HTML Entities Codes

&copy; &  &uml; &trade; &iexcl; &pound;
&amp; &lt; &gt; &yen; &euro; &reg; &plusmn; &para; &sect; &brvbar; &macr; &laquo; &middot; 

X&sup2; Y&sup3; &frac34; &frac14;  &times;  &divide;   &raquo;

18&ordm;C  &quot;  &apos;

### Emoji���� :smiley:

> Blockquotes :star:

#### GFM task lists & Emoji & fontAwesome icon emoji & editormd logo emoji :editormd-logo-5x:

- [x] :smiley: @mentions, :smiley: #refs, [links](), **formatting**, and <del>tags</del> supported :editormd-logo:;
- [x] list syntax required (any unordered or ordered list supported) :editormd-logo-3x:;
- [x] [ ] :smiley: this is a complete item :smiley:;
- [ ] []this is an incomplete item [test link](#) :fa-star: @pandao; 
- [ ] [ ]this is an incomplete item :fa-star: :fa-gear:;
    - [ ] :smiley: this is an incomplete item [test link](#) :fa-star: :fa-gear:;
    - [ ] :smiley: this is  :fa-star: :fa-gear: an incomplete item [test link](#);
 
#### ��б�� Escape

\*literal asterisks\*
            
### ��ѧ��ʽ TeX(KaTeX)
                    
$$E=mc^2$$

���ڵĹ�ʽ$$E=mc^2$$���ڵĹ�ʽ�����ڵ�$$E=mc^2$$��ʽ��

$$\(\sqrt{3x-1}+(1+x)^2\)$$
                    
$$\sin(\alpha)^{\theta}=\sum_{i=0}^{n}(x^i + \cos(f))$$

���й�ʽ��

```math
\displaystyle
\left( \sum\_{k=1}^n a\_k b\_k \right)^2
\leq
\left( \sum\_{k=1}^n a\_k^2 \right)
\left( \sum\_{k=1}^n b\_k^2 \right)
```

```katex
\displaystyle 
    \frac{1}{
        \Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{
        \frac25 \pi}} = 1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {
        1+\frac{e^{-6\pi}}
        {1+\frac{e^{-8\pi}}
         {1+\cdots} }
        } 
    }
```

```latex
f(x) = \int_{-\infty}^\infty
    \hat f(\xi)\,e^{2 \pi i \xi x}
    \,d\xi
```
                
### ��������ͼ Flowchart

```flow
st=>start: �û���½
op=>operation: ��½����
cond=>condition: ��½�ɹ� Yes or No?
e=>end: �����̨

st->op->cond
cond(yes)->e
cond(no)->op
```
                    
### ��������ͼ Sequence Diagram
                    
```seq
Andrew->China: Says Hello 
Note right of China: China thinks\nabout it 
China-->Andrew: How are you? 
Andrew->>China: I am good thanks!
```

### End