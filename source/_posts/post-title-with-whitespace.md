---
title: post title with whitespace
date: 2020-03-05 15:39:36
categories:
- [Diary, PlayStation]
- [Diary, Games]
- [Life]

tags:
- PS3
- Games
---

{% blockquote [author[linzol, source]] [link] [source_link_title] %}
tittle
{% endblockquote %}

{% blockquote %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque hendrerit lacus ut purus iaculis feugiat. Sed nec tempor elit, quis aliquam neque. Curabitur sed diam eget dolor fermentum semper at eu lorem.
{% endblockquote %}

{% blockquote David Levithan, Wide Awake %}
Do not just seek happiness for yourself. Seek happiness for all. Through kindness. Through mercy.
{% endblockquote %}

{% blockquote @DevDocs https://twitter.com/devdocs/status/356095192085962752 %}
NEW: DevDocs now comes with syntax highlighting. http://devdocs.io
{% endblockquote %}

{% blockquote Seth Godin http://sethgodin.typepad.com/seths_blog/2009/07/welcome-to-island-marketing.html Welcome to Island Marketing %}
Every interaction is both precious and an opportunity to delight.
{% endblockquote %}

{% codeblock [title] [lang:language] [url] [link text] [line_number:true first_line:1 highlight:true mark:1,4-5 wrap:true] %}
code snippet
code snippet
code snippet
code snippet
code snippet
code snippet
code snippet
{% endcodeblock %}

{% codeblock %}
alert('Hello World!');
{% endcodeblock %}


{% codeblock lang:java %}
public static void main(String[] args){
	System.out.println("Hello World")
}
{% endcodeblock %}

{% codeblock Array.map %}
array.map(callback[, thisArg])
{% endcodeblock %}

{% codeblock _.compact http://underscorejs.org/#compact Underscore.js %}
_.compact([0, 1, false, 2, '', 3]);
=> [1, 2, 3]
{% endcodeblock %}

	``` [language] [title] [url] [link text] code snippet ```

{% pullquote [class] %}
content
{% endpullquote %}


{% codeblock %}
	¿ªÊ¼
	{% jsfiddle shorttag [tabs] [skin] [width] [600] %}
	½áÊø
{% endcodeblock %}

	
{% post_link hexo-3-8-released %}