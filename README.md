wordTyping.js
===========

wordTyping.js is a library that types. This liblary works without jQuery.

<strong>example</strong><br>
![Demo](http://kinmemodoki.net/images/wordTyping.gif)<br>
Using this font in example.<br>
http://mplus-fonts.osdn.jp/mplus-bitmap-fonts/

<strong>How to use?</strong><br>
Include wordTyping.js to your page.
<pre class="brush:html;">
&lt;script src=&quot;wordTyping.js&quot;&gt;&lt;/script&gt;
</pre>
Install in javascript.
<pre class="brush:js;">
var textArea = document.getElementById("main-textarea");
var wordTyping = new WordTyping(textArea);

wordTyping.type('hello!\nInsert message!!',{
  speed:1000
  callback:function(){console.log('finished!');}
});
</pre>
