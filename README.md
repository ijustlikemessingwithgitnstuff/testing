# Header1

(TODO: Add table of contents.)

## Header2 mistmatched sides

Paragraph.

More paragraphs.

Tables:

|**Name/Sample**   | **Markup**       |
|:-----------------|:-----------------|
|  _italic_        | ` _italic_ `       |
|  **bold**         | ` *bold* `         |
|  ` code `         | `` `code` ``     |
|  ` code `        | ` {{{code}}} `     |
|  <sup>super</sup>script  | ` ^super^script `  |
|  <sub>sub</sub>script  | ` ,,sub,,script `  |
| ~~strikeout~~    | ` ~~strikeout~~ `  |

You can mix these typefaces in some ways:

|       **Markup**                    |        **Result**                 |
|:------------------------------------|:----------------------------------|
| ` _*bold* in italics_ `             | _**bold** in italics_             |
| ` *_italics_ in bold* `             | **_italics_ in bold**             |
| ` *~~strike~~ works too* `          | **~~strike~~ works too**          |
| ` ~~as well as _this_ way round~~ ` | ~~as well as _this_ way round~~   |

IN HTML

<span>
Tables:<br>
<br>
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
<tr><td> <code>~~as well as _this_ way round~~</code> </td><td> <del>as well as <i>this</i> way round</del> </td></tr>
</span></tbody></table>

### Code (mismatched header sides again)

```
{{{
def fib(n):
  if n == 0 or n == 1:
    return n
  else:
    # This recursion is not good for large numbers.
    return fib(n-1) + fib(n-2)
}}}
```

Which results in:

```
def fib(n):
  if n == 0 or n == 1:
    return n
  else:
    # This recursion is not good for large numbers.
    return fib(n-1) + fib(n-2)
```

```
<code language="xml">
<hello target="world"/>
</code>
```

IN HTML

<span>
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

<pre><code>&lt;code language="xml"&gt;<br>
&lt;hello target="world"/&gt;<br>
&lt;/code&gt;<br>
</code></pre>
</span>
