---
title: Project Name
subtitle: Lorem ipsum dolor sit amet consectetur.
image: https://raw.githubusercontent.com/BlackrockDigital/startbootstrap-agency/master/src/assets/img/portfolio/02-full.jpg
alt: Keep Exploring

caption:
  title: Explore
  subtitle: Graphic Design
  thumbnail: https://raw.githubusercontent.com/BlackrockDigital/startbootstrap-agency/master/src/assets/img/portfolio/02-thumbnail.jpg
---

This post show result from awesome Markdown techniques like jekyll. 
`Jekyll` supports to transform your plain text into static websites and blogs. 

you can easy to change style in `_utility.html` and a sample of the formatting follows.

<br>

이 포스팅은 놀라운 Markdown 기술들로 만들어진 결과물입니다.

`_utility.html`에서 스타일을 변경할 수 있으며, 서식 샘플은 아래와 같습니다.

<br>

<h2>1. HTML headings</h2>
{% highlight html %}
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>
{% endhighlight %}
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>

<br>

<h2>2. bold text</h2>
{% highlight html %}
<p>This is normal text - <b>and this is bold text</b>.</p>
{% endhighlight %}
<p>This is normal text - <b>and this is bold text</b>.</p>

<br>

<h2>3. list</h2>
<h3>a. unordered list</h3>
{% highlight html %}
- Coffee
- Tea
- Milk
{% endhighlight %}
- Coffee
- Tea
- Milk

<h3>b. ordered list</h3>
{% highlight html %}
1. Coffee
2. Tea
3. Milk
{% endhighlight %}
1. Coffee
2. Tea
3. Milk

<br>

<h2>4. hyperlink</h2>
{% highlight html %}
[naye0ng's blog](https://naye0ng.github.io)
{% endhighlight %}
[naye0ng's blog](https://naye0ng.github.io)

<br>

<h2>5. image</h2>
Try using `.width-30`, `.width-40`, `.width-50`, `.width-60`, `.width-70` and `.width-80` class! You can easily change the image width.

{% highlight html %}
![sample image]({{ site.baseurl }}/assets/img/koreaSunset.jpg)
![sample image]({{ site.baseurl }}/assets/img/koreaSunset.jpg){: .width-30}
![sample image]({{ site.baseurl }}/assets/img/koreaSunset.jpg){: .width-50}
![sample image]({{ site.baseurl }}/assets/img/koreaSunset.jpg){: .width-80}
{% endhighlight %}
![sample image]({{ site.baseurl }}/assets/img/koreaSunset.jpg)
<p></p>
![sample image]({{ site.baseurl }}/assets/img/koreaSunset.jpg){: .width-30}
![sample image]({{ site.baseurl }}/assets/img/koreaSunset.jpg){: .width-50}
![sample image]({{ site.baseurl }}/assets/img/koreaSunset.jpg){: .width-80}
<br>

<h2>5. table</h2>
{% highlight html %}
| Header 1  | Header 2  |  Header 3 |
| :-------- | :-------: | --------: |
| Content 1 | Content 2 | Content 3 |
| Content 1 | Content 2 | Content 3 |
{% endhighlight %}
| Header 1  | Header 2  |  Header 3 |
| :-------- | :-------: | --------: |
| Content 1 | Content 2 | Content 3 |
| Content 1 | Content 2 | Content 3 |

| #      | Methodology                                | Notes                 |
| ------ | ------------------------------------------ | --------------------- |
| 1      | Using `cut`                                |                       |
| 2      | Using `grep -o`                            | +5 XP for regex       |
| 3      | Using `sed -r`                             | +5 XP for regex       |
| 4      | Bash var expansion                         | +10 XP for complexity |
| 5      | Bash `read` w/ multiple vars               |                       |
| 6      | `set --` and positional parameters         | +5 XP for complexity  |
| 7      | Bash `read -d:` and `tr`                   | +10 XP for complexity |
| 8      | Bash `read -d:` and `sed 'y/set/replace/'` | +15 XP for complexity |


This is an example of a post which includes code, quotes and backtick.

you can easy to change style in `_utility.html`.

A sample of the formatting follows.

<br>

code, quotes and backtick를 포함하고 있는 게시물의 예입니다. 

 `_utility.html`에서 스타일을 변경할 수 있으며, 서식 샘플은 아래와 같습니다.

<br>

<h2>1. Code </h2>
You can add highlighting for code in `highlight.scss`.

{% highlight python %}
# test function
def test :
    print('hello world!')
{% endhighlight %}

<br>

<h2>2. Quotes</h2>
{% highlight html %}
> Hello World, This is quotes!
{% endhighlight %}
> Hello World, This is quotes!

<br>

<h2>3. `Backtick`</h2>
{% highlight html %}
`Grape-Theme`
{% endhighlight %}
`Grape-Theme`
