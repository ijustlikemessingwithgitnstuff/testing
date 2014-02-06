<table border='1'>
<thead><th>HTML Tag</th><th>Supported Attributes</th></thead>
<tbody>
<tr><td>a</td><td>title dir lang href</td></tr>
<tr><td>b</td><td>title dir lang</td></tr>
<tr><td>br</td><td>title dir lang</td></tr>
<tr><td>blockquote</td><td>title dir lang</td></tr>
<tr><td>code</td><td>title dir lang language <code>[1]</code></td></tr>
<tr><td>dd</td><td>title dir <b>lang</b></td></tr>
<tr><td>div</td><td>title dir <i>lang</i></td></tr>
<tr><td>dl</td><td>title dir <del>lang</del></td></tr>
<tr><td>dt</td><td>title dir lang</td></tr>
<tr><td>em</td><td>
The following is:<br>
<ul><li>A list<br>
</li><li>Of bulleted items<br>
<ol><li>This is a numbered sublist<br>
</li><li>Which is done by indenting further<br>
</li></ol></li><li>And back to the main bulleted list</li></ul>

<ul><li>This is also a list<br>
</li><li>With a single leading space<br>
</li><li>Notice that it is rendered<br>
<ol><li>At the same levels<br>
</li><li>As the above lists.<br>
</li></ol></li><li>Despite the different indentation levels.<br>
</li></ul><ol><li>What does this do<br>
</li><li>Let's find out</li></ol>

this should be a blockquote<br>
<br>
<blockquote>is it working<br>
am I EMPHASIZEDAZED</blockquote>

</td></tr>
<tr><td>font</td><td>

<pre><code>title dir lang face size color<br>
</code></pre>

</td></tr>
<tr><td>h1</td><td><a href='http://www.yahoo.com'>surely *at* ~~least~~ this will work</a> title dir lang</td></tr>
<tr><td>h2</td><td>

<table><thead><th> <b>Year</b> </th><th> <b>Temperature (low)</b> </th><th> <b>Temperature (high)</b> </th></thead><tbody>
<tr><td> 1900        </td><td> -10                      </td><td> 25                        </td></tr>
<tr><td> 1910        </td><td> -15                      </td><td> 30                        </td></tr>
<tr><td> 1920        </td><td> -10                      </td><td> 32                        </td></tr>
<tr><td> 1930        </td><td> <i>N/A</i>               </td><td> <i>N/A</i>                </td></tr>
<tr><td> 1940        </td><td> -2                       </td><td> 40                        </td></tr></tbody></table>

</td></tr>
<tr><td>h3</td><td>

<pre><code><br>
title<br>
dir<br>
lang<br>
</code></pre>

</td></tr>
<tr><td>h4</td><td>title dir lang</td></tr>
<tr><td>h5</td><td>title dir lang</td></tr>
<tr><td>i</td><td>title dir lang</td></tr>
<tr><td>img</td><td>title dir lang src alt border height width align</td></tr>
<tr><td>li</td><td>title dir lang</td></tr>
<tr><td>ol</td><td>title dir lang type start</td></tr>
<tr><td>p</td><td>title dir lang align</td></tr>
<tr><td>pre</td><td>title dir lang</td></tr>
<tr><td>q</td><td>title dir lang</td></tr>
<tr><td>s</td><td>title dir lang</td></tr>
<tr><td>span</td><td>title dir lang</td></tr>      <tr><td>strike</td><td>title dir lang</td></tr>      <tr><td>strong</td><td>title dir lang</td></tr>
<tr><td>sub</td><td>title dir lang</td></tr>
<tr><td>sup</td><td>title dir lang</td></tr>
<tr><td>table</td><td>title dir lang align valign cellspacing cellpadding border width height</td></tr>
<tr><td>tbody</td><td>title dir lang align valign cellspacing cellpadding border width height</td></tr>
<tr><td>td</td><td>title dir lang align valign cellspacing cellpadding border width height</td></tr>
<tr><td>tfoot</td><td>title dir lang align valign cellspacing cellpadding border width height</td></tr>
<tr><td>th</td><td>title dir lang align valign cellspacing cellpadding border width height</td></tr>
<tr><td>thead</td><td>title dir lang align valign cellspacing cellpadding border width height colspan rowspan</td></tr>
<tr><td>tr</td><td>title dir lang align valign cellspacing cellpadding border width height colspan rowspan</td></tr>
<tr><td>tt</td><td>title dir lang</td></tr>
<tr><td>u</td><td>title dir lang</td></tr>
<tr><td>ul</td><td>title dir lang type</td></tr>
<tr><td>var</td><td>

#summary The reference to the wiki syntax for Google Code projects<br>
<h1>Wiki Syntax</h1>
(TODO: Add table of contents.)<br>
<br>
<h1>Introduction</h1>

Each wiki page is stored in a .wiki file under the /wiki directory in<br>
a project's repository.  Each file's name is the same as the wiki page<br>
name.  And, each wiki file consists of optional pragma lines followed<br>
by the content of the page.<br>
<br>
<h1>Pragmas</h1>

Optional pragma lines provide metadata about the page and how it should be<br>
displayed. These lines are only processed if they appear at the top of<br>
the file.  Each pragma line begins with a pound-sign (#) and the<br>
pragma name, followed by a value.<br>
<br>
<table><thead><th> <b>Pragma</b>   </th><th> <b>Value</b>  </th></thead><tbody>
<tr><td> #summary        </td><td> One-line summary of the page </td></tr>
<tr><td> #labels         </td><td> Comma-separated list of labels (filled in automatically via the web UI) </td></tr>
<tr><td> #sidebar        </td><td> See <a href='http://code.google.com/p/support/wiki/WikiSyntax#Side_navigation'>Side navigation</a> </td></tr></tbody></table>

<h1>Wiki-style markup</h1>

<h2>Paragraphs</h2>

Use one or more blank lines to separate paragraphs.<br>
<br>
<h2>Typeface</h2>

<table><thead><th><b>Name/Sample</b>   </th><th> <b>Markup</b>       </th></thead><tbody>
<tr><td>  <i>italic</i>       </td><td> <code>_italic_</code>       </td></tr>
<tr><td>  <b>bold</b>         </td><td> <code>*bold*</code>         </td></tr>
<tr><td>  <code>code</code>         </td><td> <code>`code`</code>     </td></tr>
<tr><td>  <code>code</code>     </td><td> <code>{{{code}}}</code>     </td></tr>
<tr><td>  <sup>super</sup>script  </td><td> <code>^super^script</code>  </td></tr>
<tr><td>  <sub>sub</sub>script  </td><td> <code>,,sub,,script</code>  </td></tr>
<tr><td> <del>strikeout</del>   </td><td> <code>~~strikeout~~</code>  </td></tr></tbody></table>

You can mix these typefaces in some ways:<br>
<br>
<table><thead><th>       <b>Markup</b>                    </th><th>        <b>Result</b>                 </th></thead><tbody>
<tr><td> <code>_*bold* in italics_</code>             </td><td> <i><b>bold</b> in italics</i>             </td></tr>
<tr><td> <code>*_italics_ in bold*</code>             </td><td> <b><i>italics</i> in bold</b>             </td></tr>
<tr><td> <code>*~~strike~~ works too*</code>          </td><td> <b><del>strike</del> works too</b>          </td></tr>
<tr><td> <code>~~as well as _this_ way round~~</code> </td><td> <del>as well as <i>this</i> way round</del> </td></tr></tbody></table>

<h2>Code</h2>

If you have a multiline code block that you want to display verbatim,<br>
use the multiline code delimiter:<br>
<br>
<pre><code>{{{<br>
def fib(n):<br>
  if n == 0 or n == 1:<br>
    return n<br>
  else:<br>
    # This recursion is not good for large numbers.<br>
    return fib(n-1) + fib(n-2)<br>
}}}<br>
</code></pre>

Which results in:<br>
<br>
<pre><code>def fib(n):<br>
  if n == 0 or n == 1:<br>
    return n<br>
  else:<br>
    # This recursion is not good for large numbers.<br>
    return fib(n-1) + fib(n-2)<br>
</code></pre>

For more control over the syntax higlighting, the <code>&lt;code&gt;</code> tag allows you to specify a file extension:<br>
<br>
<pre><code>&lt;code language="xml"&gt;<br>
&lt;hello target="world"/&gt;<br>
&lt;/code&gt;<br>
</code></pre>

To disable highlighting entirely, use the <code>&lt;pre&gt;</code> tag.<br>
<br>
<h2>Headings</h2>

<pre><code>= Heading =<br>
== Subheading ==<br>
=== Level 3 ===<br>
==== Level 4 ====<br>
===== Level 5 =====<br>
====== Level 6 ======<br>
</code></pre>

<h2>Dividers</h2>

Four or more dashes on a line by themselves results in a horizontal rule.<br>
<br>
<br>
<h2>Lists</h2>

Google Code wikis support both bulleted and numbered lists. A list<br>
must be indented at least one space to be recognized as such. You can<br>
also nest lists one within the other by appropriate use of indenting:<br>
<br>
<pre><code>The following is:<br>
  * A list<br>
  * Of bulleted items<br>
    # This is a numbered sublist<br>
    # Which is done by indenting further<br>
  * And back to the main bulleted list<br>
<br>
 * This is also a list<br>
 * With a single leading space<br>
 * Notice that it is rendered<br>
  # At the same levels<br>
  # As the above lists.<br>
 * Despite the different indentation levels.<br>
</code></pre>

The following is:<br>
<ul><li>A list<br>
</li><li>Of bulleted items<br>
<ol><li>This is a numbered sublist<br>
</li><li>Which is done by indenting further<br>
</li></ol></li><li>And back to the main bulleted list</li></ul>

<ul><li>This is also a list<br>
</li><li>With a single leading space<br>
</li><li>Notice that it is rendered<br>
<ol><li>At the same levels<br>
</li><li>As the above lists.<br>
</li></ol></li><li>Despite the different indentation levels.</li></ul>

<h2>Quoting</h2>

Block quotes place emphasis on a particular extract of text in your<br>
page. Block quotes are created by indenting a paragraph by at least<br>
one space:<br>
<br>
<pre><code>Someone once said:<br>
<br>
  This sentence will be quoted in the future as the canonical example<br>
  of a quote that is so important that it should be visually separate<br>
  from the rest of the text in which it appears.<br>
</code></pre>

Someone once said:<br>
<br>
<blockquote>This sentence will be quoted in the future as the canonical example<br>
of a quote that is so important that it should be visually separate<br>
from the rest of the text in which it appears.</blockquote>

<h2>Links</h2>

Links are central to the wiki principle, as they create the web of<br>
content. Google Code wiki permits both internal (within the wiki) and<br>
external links, and in some cases automatically creates a link when it<br>
recognizes either a WikiWord or an URL.<br>
<br>
<h3>Internal wiki links</h3>

Internal links within a wiki are created using the syntax below. If<br>
you add a wiki link to a page that does not exist, the link will<br>
appear with a LittleLink<a href='wiki/WikiSyntax'>?</a> to project committers and<br>
owners. Clicking that link will take you to the page creation form<br>
where you can enter content for that page.<br>
<br>
If you are not logged in, wiki links that point to non-existent pages<br>
will appear as plain text, without the link to the page creation<br>
form. When you create the target page,<br>
the link will become a normal hyperlink for all viewers of<br>
the page.<br>
<br>
<pre><code>WikiSyntax is identified and linked automatically<br>
<br>
Wikipage is not identified, so if you have a page named [Wikipage] you<br>
need to link it explicitly.<br>
<br>
If the WikiSyntax page is actually about reindeers, you can provide a<br>
description, so that people know you are actually linking to a page on<br>
[WikiSyntax reindeer flotillas].<br>
<br>
If you want to mention !WikiSyntax without it being autolinked, use an<br>
exclamation mark to prevent linking.<br>
</code></pre>

<a href='wiki/WikiSyntax'>WikiSyntax</a> is identified and linked automatically<br>
<br>
Wikipage is not identified, so if you have a page named <a href='wiki/Wikipage'>Wikipage</a> you<br>
need to link it explicitly.<br>
<br>
If the <a href='wiki/WikiSyntax'>WikiSyntax</a> page is actually about reindeers, you can provide a<br>
description, so that people know you are actually linking to a page on<br>
<a href='wiki/WikiSyntax'>reindeer flotillas</a>.<br>
<br>
If you want to mention WikiSyntax without it being autolinked, use an<br>
exclamation mark to prevent linking.<br>
<br>
<h3>Links to anchors within a page</h3>

Each heading defines a HTML anchor with the same name as the heading, but with spaces replaced by underscores. You can<br>
create a link to a specific heading on a page like this:<br>
<br>
<pre><code>[WikiSyntax#Wiki-style_markup]<br>
</code></pre>

And it will render as: <a href='wiki/WikiSyntax#Wiki-style_markup'>WikiSyntax#Wiki-style_markup</a>.<br>
<br>
<h3>Links to issues and revisions</h3>

You can easily link to issues and revisions using the following syntax.<br>
<br>
<ul><li><code>issue 123</code> will be autolinked to issue number 123 in the current project.  You can include a <code>#</code> or not.  If the issue has been closed, the link will appear as a cross-out rather than an underline.  Hovering your mouse over such a link shows the issue summary.</li></ul>

<ul><li><code>issue PROJECTNAME:122</code> will be autolinked to that issue number in the specified project.  This is useful when your project depends on work being done in related projects.</li></ul>

<ul><li><code>r123</code> will be autolinked to the revision detail page for that revision in the current project.</li></ul>

There is currently no way to disable this type of autolinking. See [issue 996](https://code.google.com/p/support/issues/detail?id=996).<br>
<br>
<pre><code>For example: Please add a comment on issue 123 rather than adding more review comments to r456. <br>
</code></pre>

Renders as: Please add a comment on [issue 123](https://code.google.com/p/support/issues/detail?id=123) rather than adding more review comments to [r456](https://code.google.com/p/support/source/detail?r=456).<br>
<br>
<br>
<h3>Links to external pages</h3>

You can of course link to external pages from your own wiki pages,<br>
using a syntax similar to that for internal links:<br>
<br>
<pre><code>Plain URLs such as http://www.google.com/ or ftp://ftp.kernel.org/ are<br>
automatically made into links.<br>
<br>
You can also provide some descriptive text. For example, the following<br>
link points to the [http://www.google.com Google home page].<br>
<br>
If your link points to an image, it will get inserted as an image tag<br>
into the page:<br>
<br>
http://code.google.com/images/code_sm.png<br>
<br>
You can also make the image into a link, by setting the image URL as<br>
the description of the URL you want to link:<br>
<br>
[http://code.google.com/ http://code.google.com/images/code_sm.png]<br>
</code></pre>

Plain URLs such as <a href='http://www.google.com/'>http://www.google.com/</a> or <a href='ftp://ftp.kernel.org/'>ftp://ftp.kernel.org/</a> are<br>
automatically made into links.<br>
<br>
You can also provide some descriptive text. For example, the following<br>
link points to the <a href='http://www.google.com'>Google home page</a>.<br>
<br>
You can also make the image into a link, by setting the image URL as<br>
the description of the URL you want to link:<br>
<br>
<pre><code>[http://code.google.com/ http://code.google.com/images/code_sm.png]<br>
</code></pre>

<a href='http://code.google.com/'><img src='http://code.google.com/images/code_sm.png' /></a>


<h3>Links to images</h3>

If your link points to an image (that is, if it ends in <code>.png</code>,<br>
<code>.gif</code>, <code>.jpg</code> or <code>.jpeg</code>), it will get inserted as an image into the<br>
page:<br>
<br>
<pre><code>http://code.google.com/images/code_sm.png<br>
</code></pre>

<img src='http://code.google.com/images/code_sm.png' />

If the image is produced by a server-side script, you may need to add a nonsense query string parameter to the end so that the URL ends with a supported image filename extension.<br>
<br>
<pre><code>http://chart.apis.google.com/chart?chs=200x125&amp;chd=t:48.14,33.79,19.77|83.18,18.73,12.04&amp;cht=bvg&amp;nonsense=something_that_ends_with.png<br>
</code></pre>

<img src='http://chart.apis.google.com/chart?chs=200x125&chd=t:48.14,33.79,19.77|83.18,18.73,12.04&cht=bvg&nonsense=something_that_ends_with.png' />

<h2>Tables</h2>

Tables are created by entering the content of each cell separated by<br>
<code>||</code> delimiters. You can insert other inline wiki syntax in table<br>
cells, including typeface formatting and links.<br>
<br>
<pre><code>|| *Year* || *Temperature (low)* || *Temperature (high)* ||<br>
|| 1900 || -10 || 25 ||<br>
|| 1910 || -15 || 30 ||<br>
|| 1920 || -10 || 32 ||<br>
|| 1930 || _N/A_ || _N/A_ ||<br>
|| 1940 || -2 || 40 ||<br>
</code></pre>

<table><thead><th> <b>Year</b> </th><th> <b>Temperature (low)</b> </th><th> <b>Temperature (high)</b> </th></thead><tbody>
<tr><td> 1900        </td><td> -10                      </td><td> 25                        </td></tr>
<tr><td> 1910        </td><td> -15                      </td><td> 30                        </td></tr>
<tr><td> 1920        </td><td> -10                      </td><td> 32                        </td></tr>
<tr><td> 1930        </td><td> <i>N/A</i>               </td><td> <i>N/A</i>                </td></tr>
<tr><td> 1940        </td><td> -2                       </td><td> 40                        </td></tr></tbody></table>








<h1>HTML support</h1>
To aid in the presentation of a wiki page there is some support for HTML. HTML tags are only supported in wiki pages, not in page comments.<br>
<br>
HTML syntax can be used in conjunction with wiki syntax, but it is recommended against doing so where possible.<!-- Also, avoid blank lines between list items. --><br>
<br>
The following HTML tags and attributes are currently supported:<br>
<br>
<table border='1'>
<thead><th>HTML Tag</th><th>Supported Attributes</th></thead>
<tbody>
<tr><td>a</td><td>title dir lang href</td></tr>
<tr><td>b</td><td>title dir lang</td></tr>
<tr><td>br</td><td>title dir lang</td></tr>
<tr><td>blockquote</td><td>title dir lang</td></tr>
<tr><td>code</td><td>title dir lang language <code>[1]</code></td></tr>
<tr><td>dd</td><td>title dir lang</td></tr>
<tr><td>div</td><td>title dir lang</td></tr>
<tr><td>dl</td><td>title dir lang</td></tr>
<tr><td>dt</td><td>title dir lang</td></tr>
<tr><td>em</td><td>title dir lang</td></tr>
<tr><td>font</td><td>title dir lang face size color</td></tr>
<tr><td>h1</td><td>title dir lang</td></tr>
<tr><td>h2</td><td>title dir lang</td></tr>
<tr><td>h3</td><td>title dir lang</td></tr>
<tr><td>h4</td><td>title dir lang</td></tr>
<tr><td>h5</td><td>title dir lang</td></tr>
<tr><td>i</td><td>title dir lang</td></tr>
<tr><td>img</td><td>title dir lang src alt border height width align</td></tr>
<tr><td>li</td><td>title dir lang</td></tr>
<tr><td>ol</td><td>title dir lang type start</td></tr>
<tr><td>p</td><td>title dir lang align</td></tr>
<tr><td>pre</td><td>title dir lang</td></tr>
<tr><td>q</td><td>title dir lang</td></tr>
<tr><td>s</td><td>title dir lang</td></tr>
<tr><td>span</td><td>title dir lang</td></tr>      <tr><td>strike</td><td>title dir lang</td></tr>      <tr><td>strong</td><td>title dir lang</td></tr>
<tr><td>sub</td><td>title dir lang</td></tr>
<tr><td>sup</td><td>title dir lang</td></tr>
<tr><td>table</td><td>title dir lang align valign cellspacing cellpadding border width height</td></tr>
<tr><td>tbody</td><td>title dir lang align valign cellspacing cellpadding border width height</td></tr>
<tr><td>td</td><td>title dir lang align valign cellspacing cellpadding border width height</td></tr>
<tr><td>tfoot</td><td>title dir lang align valign cellspacing cellpadding border width height</td></tr>
<tr><td>th</td><td>title dir lang align valign cellspacing cellpadding border width height</td></tr>
<tr><td>thead</td><td>title dir lang align valign cellspacing cellpadding border width height colspan rowspan</td></tr>
<tr><td>tr</td><td>title dir lang align valign cellspacing cellpadding border width height colspan rowspan</td></tr>
<tr><td>tt</td><td>title dir lang</td></tr>
<tr><td>u</td><td>title dir lang</td></tr>
<tr><td>ul</td><td>title dir lang type</td></tr>
<tr><td>var</td><td>title dir lang</td></tr>      </tbody>
</table>

<code>[1]</code> The language attribute of the code tag is the file extension of the language used in the code block. It is used as a hint for the syntax highlighter.<br>
<br>
<h2>Escaping HTML Tags</h2>

When you want to display html tags directly on your wiki page (as opposed to rendered), you will need to escape each HTML tag.<br>
<br>
HTML tags can be escaped as shown in the table below:<br>
<table border='1'>
<thead><th>Markup</th><th>Result</th></thead>
<tbody>
<tr><td> <code>`&lt;hr&gt;`</code></td><td><code>&lt;hr&gt;</code></td></tr>
<tr><td> <code>{{{&lt;hr&gt;}}}</code></td><td><code>&lt;hr&gt;</code></td></tr>
</tbody>
</table>

<br />

<h1>Comments</h1>

The wiki supports embedded comments to help explain the contents of a wiki page. Anything inside the comment block is removed from the rendered page, but is visible when editing or viewing the source for that page.<br>
<br>
<pre><code>&lt;wiki:comment&gt;<br>
This text will be removed from the rendered page.<br>
&lt;/wiki:comment&gt;<br>
</code></pre>

<h1>+1 Button</h1>

Use <code>&lt;g:plusone&gt;&lt;/g:plusone&gt;</code> to add a <a href='http://www.google.com/+1/button/'>+1 button</a> to the page. Example:<br>
<br>
<pre><code>&lt;g:plusone size="medium"&gt;&lt;/g:plusone&gt;<br>
</code></pre>

<script type='text/javascript' src='https://apis.google.com/js/plusone.js'></script><g:plusone size='medium'></g:plusone><br>
<br>
The count, size, and href parameters are supported; see <a href='http://code.google.com/apis/+1button/'>http://code.google.com/apis/+1button/</a> for documentation.<br>
<br>
<h1>Gadgets</h1>

You can embed <a href='http://www.google.com/ig/directory?synd=open'>Gadgets</a> on your wiki pages with the following syntax:<br>
<br>
<pre><code>&lt;wiki:gadget url="http://example.com/gadget.xml" height="200" border="0" /&gt; <br>
</code></pre>

Valid attributes are:<br>
<ul><li><code>url</code>: the URL of the gadget<br>
</li><li><code>width</code>: the width of the gadget<br>
</li><li><code>height</code>: the height of the gadget<br>
</li><li><code>title</code>: a title to display above the gadget<br>
</li><li><code>border</code>: "0" or "1", whether to draw a border around the gadget<br>
</li><li><code>up_*</code>: Gadget user preference parameters<br>
</li><li><code>caja</code>: "0" or "1", whether to use Caja to render the gadget.  <a href='http://code.google.com/p/google-caja'>Caja</a> helps protect users from malicious or accidental errors in third party gadgets.</li></ul>

WorkingWithGoogleGadgets describes how to create gadgets for Google Code. It also provides  a few helpful suggestions that can make it easier to publish gadgets and to integrate with other Google products such as iGoogle.<br>
<br>
InterestingDeveloperGadgets shows some sample gadgets you may want to include on your project pages.<br>
<br>
<h1>Videos</h1>

You can embed videos with the following syntax:<br>
<br>
<pre><code>&lt;wiki:video url="http://www.youtube.com/watch?v=3LkNlTNHZzE"/&gt;<br>
</code></pre>

Valid attributes are:<br>
<ul><li><code>url</code>: the URL of the video<br>
</li><li><code>width</code>: the width of the embedded video<br>
</li><li><code>height</code>: the height of the embedded video</li></ul>

Right now we support videos from YouTube,. Other video sites may be embeddable via a gadget, as described above.<br>
<br>
<h1>Navigation</h1>
<h2>Table of Contents</h2>

An inline table of contents can be generated from page headers on a wiki page. Add the following syntax to a page in the location the table of contents should be displayed:<br>
<br>
<pre><code>&lt;wiki:toc max_depth="1" /&gt;<br>
</code></pre>

Valid attributes are:<br>
<ul><li><code>max_depth</code>: the maximum header depth to display in the table of contents</li></ul>

<h2>Side navigation</h2>

You can specify the sidebar for a wiki page by selecting another wiki page that defines your side navigation. The <a href='http://code.google.com/p/guava-libraries/wiki/GuavaExplained?tm=6'>Guava project</a> uses the sidebar extensively across its wiki.<br>
<br>
One way of adding a sidebar is by setting the #sidebar pragma, as shown below. Alternatively, the sidebar pragma can be left blank if no side navigation is desired.<br>
<br>
<table><thead><th> #sidebar TableOfContents </th></thead><tbody></tbody></table>

The side navigation that is defined should be in the format of a simple list, as shown below.<br>
<br>
<pre><code>  * [Articles HOWTO articles]<br>
    * [ArticlesXSS Web security]<br>
    * [ArticlesDom DOM manipulation]<br>
    * [ArticlesStyle CSS and style]<br>
    * [ArticlesTips Tips and tricks]<br>
  * [DOMReference DOM reference]<br>
  * [HTMLElements HTML reference]<br>
  * [CSSReference CSS reference]<br>
</code></pre>

A default sidebar page can also be specified for all wiki pages by project owners through the Wiki settings in the Administer tab. If a #sidebar pragma is also specified, it will take precedence on the page.<br>
<br>
<h1>Localizing Wiki Content</h1>

Along with the default language for the wiki, which can be set through the Wiki settings in the Administer tab, additional languages are also supported. If more than one language is available, based on a user's language preference (e.g. browser language), the wiki will try to serve the page for the appropriate language. If no wiki page exists for that language, it will fall back to the default language. Comments, however, are shared amongst all translations of a wiki page.<br>
<br>
New translations for a page cannot be added through the web interface and have to be added through the Subversion repository.<br>
<br>
To add a translation of a page, first checkout the wiki from Subversion: <br />
<code>svn checkout https://</code><b>yourproject</b><code>.googlecode.com/svn/wiki/</code> <b>yourdirectory</b> <code>-username</code> <b>yourusername</b>

Then create a new directory under /wiki/ using the two letter ISO-639 code as the name of that directory. Place all translated files in the new directory and submit those changes to the Subversion repository.<br>
<br>
The following is an example of a valid wiki directory:<br>
<pre><code>wiki/<br>
   ja/<br>
      ProjectHistory.wiki<br>
      StyleGuide.wiki<br>
   zh-Hans/<br>
      ProjectHistory.wiki<br>
      StyleGuide.wiki<br>
   zh-Hant/<br>
      ProjectHistory.wiki<br>
      StyleGuide.wiki<br>
   ProjectHistory.wiki<br>
   StyleGuide.wiki<br>
</code></pre>

Once the files have been submitted to the project's subversion repository, they can now be edited through the wiki's web editor. The process is the same for Mercurial or Git projects, except that the wiki lives in the root directory (not wiki/) of <code>https://wiki.</code><b>yourproject</b><code>.googlecode.com/hg/</code> or <code>https://wiki.</code><b>yourproject</b><code>.googlecode.com/git/</code>.<br>
<br>
Note: The wiki accepts a subset of ISO-639 two letter language codes, where a few of the codes (such as zh_Hans) contain locale-specific codes. Such locale-specific codes should use a hyphen (zh-Hans) separator. A few example language codes have been specified in the table below.<br>
<br>
<table border='1'>
<tbody><tr>
<th> Language (Locale)</th>
<th> Directory Name<br>
</th>
</tr>
<tr>
<td>Arabic</td>
<td>ar</td>
</tr>
<tr>
<td>Bulgarian</td>
<td>bg</td>
</tr>
<tr>
<td>Chinese (China)</td>
<td>zh-Hans</td>
</tr>
<tr>
<td>Chinese (Taiwan)</td>
<td>zh-Hant</td>
</tr>
<tr>
<td>Croatian</td>
<td>hr</td>
</tr>
<tr>
<td>Czech</td>
<td>cs</td>
</tr>
<tr>
<td>Danish</td>
<td>da</td>
</tr>
<tr>
<td>Dutch</td>
<td>nl</td>
</tr>
<tr>
<td>English (United Kingdom)</td>
<td>en-GB</td>
</tr>
<tr>
<td>English (United States)</td>
<td>en-US</td>
</tr>
<tr>
<td>Finnish</td>
<td>fi</td>
</tr>
<tr>
<td>French</td>
<td>fr</td>
</tr>
<tr>
<td>German</td>
<td>de</td>
</tr>
<tr>
<td>Greek</td>
<td>el</td>
</tr>
<tr>
<td>Hebrew</td>
<td>he</td>
</tr>
<tr>
<td>Hungarian</td>
<td>hu</td>
</tr>
<tr>
<td>Italian</td>
<td>it</td>
</tr>
<tr>
<td>Japanese</td>
<td>ja</td>
</tr>
<tr>
<td>Korean</td>
<td>ko</td>
</tr>
<tr>
<td>Norwegian</td>
<td>no</td>
</tr>
<tr>
<td>Polish</td>
<td>pl</td>
</tr>
<tr>
<td>Portuguese (Brazil)</td>
<td>pt-BR</td>
</tr>
<tr>
<td>Romanian</td>
<td>ro</td>
</tr>
<tr>
<td>Russian</td>
<td>ru</td>
</tr>
<tr>
<td>Slovak</td>
<td>sk</td>
</tr>
<tr>
<td>Spanish</td>
<td>es</td>
</tr>
<tr>
<td>Swedish</td>
<td>sv</td>
</tr>
<tr>
<td>Turkish</td>
<td>tr</td>
</tr>
</tbody></table>

<i>The content on this page created by Google is licensed under the <a href='http://creativecommons.org/licenses/by/3.0/'>Creative Commons Attribution 3.0 License</a>.  User-generated content is not included in this license.</i>

</td></tr>      </tbody>
</table>
