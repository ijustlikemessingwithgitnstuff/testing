~~uniquenessy~~


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
<tr><td>dl</td><td>title dir <s>lang</s></td></tr>
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

<code>title dir lang face size color
</code>

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
<tr><td>var</td><td>

#summary The reference to the wiki syntax for Google Code projects<br>
# Wiki Syntax<br>
(TODO: Add table of contents.)<br>
<br>
# Introduction<br>
<br>
Each wiki page is stored in a .wiki file under the /wiki directory in<br>
a project's repository.  Each file's name is the same as the wiki page<br>
name.  And, each wiki file consists of optional pragma lines followed<br>
by the content of the page.<br>
<br>
# Pragmas<br>
<br>
Optional pragma lines provide metadata about the page and how it should be<br>
displayed. These lines are only processed if they appear at the top of<br>
the file.  Each pragma line begins with a pound-sign (#) and the<br>
pragma name, followed by a value.<br>
<br>
<table><thead><th> <b>Pragma</b>   </th><th> <b>Value</b>  </th></thead><tbody>
<tr><td> #summary        </td><td> One-line summary of the page </td></tr>
<tr><td> #labels         </td><td> Comma-separated list of labels (filled in automatically via the web UI) </td></tr>
<tr><td> #sidebar        </td><td> See <a href='http://code.google.com/p/support/wiki/WikiSyntax#Side_navigation'>Side navigation</a> </td></tr></tbody></table>

# Wiki-style markup<br>
<br>
## Paragraphs<br>
<br>
Use one or more blank lines to separate paragraphs.<br>
<br>
## Typeface<br>
<br>
<table><thead><th><b>Name/Sample</b>   </th><th> <b>Markup</b>       </th></thead><tbody>
<tr><td>  <i>italic</i>       </td><td> <code>_italic_</code>       </td></tr>
<tr><td>  <b>bold</b>         </td><td> <code>*bold*</code>         </td></tr>
<tr><td>  <code>code</code>         </td><td> <code>`code`</code>     </td></tr>
<tr><td>  <code>code</code>     </td><td> <code>{{{code}}}</code>     </td></tr>
<tr><td>  <sup>super</sup>script  </td><td> <code>^super^script</code>  </td></tr>
<tr><td>  <sub>sub</sub>script  </td><td> <code>,,sub,,script</code>  </td></tr>
<tr><td> <s>strikeout</s>    </td><td> <code>~~strikeout~~</code>  </td></tr></tbody></table>

You can mix these typefaces in some ways:<br>
<br>
<table><thead><th>       <b>Markup</b>                    </th><th>        <b>Result</b>                 </th></thead><tbody>
<tr><td> <code>_*bold* in italics_</code>             </td><td> <i><b>bold</b> in italics</i>             </td></tr>
<tr><td> <code>*_italics_ in bold*</code>             </td><td> <b><i>italics</i> in bold</b>             </td></tr>
<tr><td> <code>*~~strike~~ works too*</code>          </td><td> <b><s>strike</s> works too</b>          </td></tr>
<tr><td> <code>~~as well as _this_ way round~~</code> </td><td> <s>as well as <i>this</i> way round</s> </td></tr></tbody></table>

## Code<br>
<br>
If you have a multiline code block that you want to display verbatim,<br>
use the multiline code delimiter:<br>
<br>
<code>{{{
def fib(n):
  if n == 0 or n == 1:
    return n
  else:
    # This recursion is not good for large numbers.
    return fib(n-1) + fib(n-2)
}}}
</code>

Which results in:<br>
<br>
<code>def fib(n):
  if n == 0 or n == 1:
    return n
  else:
    # This recursion is not good for large numbers.
    return fib(n-1) + fib(n-2)
</code>

For more control over the syntax higlighting, the <code><code></code> tag allows you to specify a file extension:<br>
<br>
<code><code language="xml">
<hello target="world"/>
</code>
</code>

To disable highlighting entirely, use the <code><pre></code> tag.<br>
<br>
## Headings<br>
<br>
<code>= Heading =
== Subheading ==
=== Level 3 ===
==== Level 4 ====
===== Level 5 =====
====== Level 6 ======
</code>

## Dividers<br>
<br>
Four or more dashes on a line by themselves results in a horizontal rule.<br>
<br>
<br>
## Lists<br>
<br>
Google Code wikis support both bulleted and numbered lists. A list<br>
must be indented at least one space to be recognized as such. You can<br>
also nest lists one within the other by appropriate use of indenting:<br>
<br>
<code>The following is:
  * A list
  * Of bulleted items
    # This is a numbered sublist
    # Which is done by indenting further
  * And back to the main bulleted list

 * This is also a list
 * With a single leading space
 * Notice that it is rendered
  # At the same levels
  # As the above lists.
 * Despite the different indentation levels.
</code>

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

## Quoting<br>
<br>
Block quotes place emphasis on a particular extract of text in your<br>
page. Block quotes are created by indenting a paragraph by at least<br>
one space:<br>
<br>
<code>Someone once said:

  This sentence will be quoted in the future as the canonical example
  of a quote that is so important that it should be visually separate
  from the rest of the text in which it appears.
</code>

Someone once said:<br>
<br>
<blockquote>This sentence will be quoted in the future as the canonical example<br>
of a quote that is so important that it should be visually separate<br>
from the rest of the text in which it appears.</blockquote>

## Links<br>
<br>
Links are central to the wiki principle, as they create the web of<br>
content. Google Code wiki permits both internal (within the wiki) and<br>
external links, and in some cases automatically creates a link when it<br>
recognizes either a WikiWord or an URL.<br>
<br>
### Internal wiki links<br>
<br>
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
<code>WikiSyntax is identified and linked automatically

Wikipage is not identified, so if you have a page named [Wikipage] you
need to link it explicitly.

If the WikiSyntax page is actually about reindeers, you can provide a
description, so that people know you are actually linking to a page on
[WikiSyntax reindeer flotillas].

If you want to mention !WikiSyntax without it being autolinked, use an
exclamation mark to prevent linking.
</code>

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
### Links to anchors within a page<br>
<br>
Each heading defines a HTML anchor with the same name as the heading, but with spaces replaced by underscores. You can<br>
create a link to a specific heading on a page like this:<br>
<br>
<code>[WikiSyntax#Wiki-style_markup]
</code>

And it will render as: <a href='wiki/WikiSyntax#Wiki-style_markup'>WikiSyntax#Wiki-style_markup</a>.<br>
<br>
### Links to issues and revisions<br>
<br>
You can easily link to issues and revisions using the following syntax.<br>
<br>
<ul><li><code>issue 123</code> will be autolinked to issue number 123 in the current project.  You can include a <code>#</code> or not.  If the issue has been closed, the link will appear as a cross-out rather than an underline.  Hovering your mouse over such a link shows the issue summary.</li></ul>

<ul><li><code>issue PROJECTNAME:122</code> will be autolinked to that issue number in the specified project.  This is useful when your project depends on work being done in related projects.</li></ul>

<ul><li><code>r123</code> will be autolinked to the revision detail page for that revision in the current project.</li></ul>

There is currently no way to disable this type of autolinking. See [issue 996](https://code.google.com/p/support/issues/detail?id=996).<br>
<br>
<code>For example: Please add a comment on issue 123 rather than adding more review comments to r456. 
</code>

Renders as: Please add a comment on [issue 123](https://code.google.com/p/support/issues/detail?id=123) rather than adding more review comments to [r456](https://code.google.com/p/support/source/detail?r=456).<br>
<br>
<br>
### Links to external pages<br>
<br>
You can of course link to external pages from your own wiki pages,<br>
using a syntax similar to that for internal links:<br>
<br>
<code>Plain URLs such as http://www.google.com/ or ftp://ftp.kernel.org/ are
automatically made into links.

You can also provide some descriptive text. For example, the following
link points to the [http://www.google.com Google home page].

If your link points to an image, it will get inserted as an image tag
into the page:

http://code.google.com/images/code_sm.png

You can also make the image into a link, by setting the image URL as
the description of the URL you want to link:

[http://code.google.com/ http://code.google.com/images/code_sm.png]
</code>

Plain URLs such as <a href='http://www.google.com/'></a> or <a href='ftp://ftp.kernel.org/'></a> are<br>
automatically made into links.<br>
<br>
You can also provide some descriptive text. For example, the following<br>
link points to the <a href='http://www.google.com'>Google home page</a>.<br>
<br>
You can also make the image into a link, by setting the image URL as<br>
the description of the URL you want to link:<br>
<br>
<code>[http://code.google.com/ http://code.google.com/images/code_sm.png]
</code>

<a href='http://code.google.com/'><img src='http://code.google.com/images/code_sm.png' /></a>


### Links to images<br>
<br>
If your link points to an image (that is, if it ends in <code>.png</code>,<br>
<code>.gif</code>, <code>.jpg</code> or <code>.jpeg</code>), it will get inserted as an image into the<br>
page:<br>
<br>
<code>http://code.google.com/images/code_sm.png
</code>

<a href='http://code.google.com/images/code_sm.png'></a>

If the image is produced by a server-side script, you may need to add a nonsense query string parameter to the end so that the URL ends with a supported image filename extension.<br>
<br>
<code>http://chart.apis.google.com/chart?chs=200x125&chd=t:48.14,33.79,19.77|83.18,18.73,12.04&cht=bvg&nonsense=something_that_ends_with.png
</code>

<a href='http://chart.apis.google.com/chart?chs=200x125&chd=t:48.14,33.79,19.77|83.18,18.73,12.04&cht=bvg&nonsense=something_that_ends_with.png'></a>

## Tables<br>
<br>
Tables are created by entering the content of each cell separated by<br>
<code>||</code> delimiters. You can insert other inline wiki syntax in table<br>
cells, including typeface formatting and links.<br>
<br>
<code>|| *Year* || *Temperature (low)* || *Temperature (high)* ||
|| 1900 || -10 || 25 ||
|| 1910 || -15 || 30 ||
|| 1920 || -10 || 32 ||
|| 1930 || _N/A_ || _N/A_ ||
|| 1940 || -2 || 40 ||
</code>

<table><thead><th> <b>Year</b> </th><th> <b>Temperature (low)</b> </th><th> <b>Temperature (high)</b> </th></thead><tbody>
<tr><td> 1900        </td><td> -10                      </td><td> 25                        </td></tr>
<tr><td> 1910        </td><td> -15                      </td><td> 30                        </td></tr>
<tr><td> 1920        </td><td> -10                      </td><td> 32                        </td></tr>
<tr><td> 1930        </td><td> <i>N/A</i>               </td><td> <i>N/A</i>                </td></tr>
<tr><td> 1940        </td><td> -2                       </td><td> 40                        </td></tr></tbody></table>








# HTML support<br>
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
<tr><td>dd</td><td>title dir <b>lang</b></td></tr>
<tr><td>div</td><td>title dir <i>lang</i></td></tr>
<tr><td>dl</td><td>title dir <s>lang</s></td></tr>
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
</li></ol></li><li>Despite the different indentation levels.</li></ul>

</td></tr>
<tr><td>font</td><td>

<code>title dir lang face size color
</code>

</td></tr>
<tr><td>h1</td><td><a href='wiki/surely'>at least this will work</a>(<a href='http://www.yahoo.com'></a>) title dir lang</td></tr>
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
## Escaping HTML Tags<br>
<br>
When you want to display html tags directly on your wiki page (as opposed to rendered), you will need to escape each HTML tag.<br>
<br>
HTML tags can be escaped as shown in the table below:<br>
<table border='1'>
<thead><th>Markup</th><th>Result</th></thead>
<tbody>
<tr><td> <code>`<hr>`</code></td><td><code><hr></code></td></tr>
<tr><td> <code>{{{<hr>}}}</code></td><td><code><hr></code></td></tr>
</tbody>
</table>

<br />

# Comments<br>
<br>
The wiki supports embedded comments to help explain the contents of a wiki page. Anything inside the comment block is removed from the rendered page, but is visible when editing or viewing the source for that page.<br>
<br>
<code><wiki:comment>
This text will be removed from the rendered page.
</wiki:comment>
</code>

# +1 Button<br>
<br>
Use <code><g:plusone></g:plusone></code> to add a <a href='http://www.google.com/+1/button/'>+1 button</a> to the page. Example:<br>
<br>
<code><g:plusone size="medium"></g:plusone>
</code>

<script type='text/javascript' src='https://apis.google.com/js/plusone.js'></script><g:plusone size='medium'></g:plusone><br>
<br>
The count, size, and href parameters are supported; see <a href='http://code.google.com/apis/+1button/'></a> for documentation.<br>
<br>
<br>
g</td></tr>      </tbody>
</table>
