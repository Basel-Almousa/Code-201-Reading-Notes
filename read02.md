# **How to add markup to the text that appears on your pages?**
- Structural markup: the elements that you can use to describe both headings and paragraphs.
- Semantic markup: which provides extra information; such
as where emphasis is placed in a sentence, that something
you have written is a quotation (and who said it), the
meaning of acronyms, and so on.
## **Headings**
headings are defined as the following: 
HTML has six "levels" of
headings:
- -h1- is used for main headings
- -h2- is used for subheadings If there are further sections under the subheadings then the
- -h3- element is used, and so on... Browsers display the contents of headings at different sizes. The
contents of an -h1- element is
the largest, and the contents of
an -h6- element is the smallest.
The exact size at which each
browser shows the headings
can vary slightly. Users can also
adjust the size of text in their
browser. You will see how to
control the size of text, its color,
and the fonts used when we
come to look at CSS. 
# **Paragraphs**
To create a paragraph, surround
the words that make up the
paragraph with an opening -p-
tag and closing -/p- tag.
By default, a browser will show
each paragraph on a new line
with some space between it and
any subsequent paragraphs.
# **Bold & Italic**
- **BOLD**  
By enclosing words in the tags
\<b> and \</b> we can make
characters appear bold.
The \<b> element also represents
a section of text that would be
presented in a visually different
way (for example key words in a
paragraph) although the use of
the \<b> element does not imply
any additional meaning.
- **Italic**  
By enclosing words in the tags
\<i> and \</i> we can make
characters appear italic.
The \<i> element also represents
a section of text that would be
said in a different way from
surrounding content — such as
technical terms, names of ships,
foreign words, thoughts, or other
terms that would usually be
italicized.
# **Superscript & Subscrip**
- \<sup>  
The \<sup> element is used
to contain characters that
should be superscript such
as the suffixes of dates or
mathematical concepts like
raising a number to a power such
as 22
- \<sub>  
The \<sub> element is used to
contain characters that should
be subscript. It is commonly
used with foot notes or chemical formulas such as H20.
# **White Space**
>In order to make code easier to
read, web page authors often
add extra spaces or start some
elements on new lines.
When the browser comes across
two or more spaces next to each
other, it only displays one space.
Similarly if it comes across a line
break, it treats that as a single
space too. This is known as
white space collapsing.
You will often see that web page
authors take advantage of white
space collapsing to indent their
code in order to make it easier
to follow.
# **Line Breaks & Horizontal Rules**
- \<br />  
>As you have already seen, the
browser will automatically show
each new paragraph or heading
on a new line. But if you wanted
to add a line break inside the
middle of a paragraph you can
use the line break tag \<br />.
- \<hr />
>To create a break between
themes — such as a change of
topic in a book or a new scene
in a play — you can add a
horizontal rule between sections
using the \<hr /> tag.
There are few elements that
do not have any words between
an opening and closing tag. They
are known as empty elements
and they are written differently.
An empty element usually
has only one tag. Before the
closing angled bracket of an
empty element there will often
be a space and a forward slash
character. Some web page
authors miss this out but it is a
good habit to get into.
# **Visual Editors & Their Code views**
Content management systems and HTML editors such as Dreamweaver
usually have two views of the page you are creating: a visual editor and a
code view.
- Visual editors  
often resemble
word processors. Although
each editor will differ slightly,
there are some features that
are common to most editors
that allow you to control the
presentation of text.
- Code views   
show you the code
created by the visual editor so
you can manually edit it, or so
you can just enter new code
yourself. It is often activated
using a button with an icon
that says HTML or has angled
brackets. White space may be
added to the code by the editor
to make the code easier to read.
 # **Semantic Markup**
 There are some text elements that are not intended to affect the
structure of your web pages, but they do add extra information to the
pages — they are known as semantic markup.
# **Strong & Emphasis**
- \<strong>  
The use of the \<strong>
element indicates that its
content has strong importance.
For example, the words
contained in this element might
be said with strong emphasis.
By default, browsers will show
the contents of a \<strong>
element in bold.
- \<em>  
The \<em> element indicates
emphasis that subtly changes
the meaning of a sentence.
By default browsers will show
the contents of an \<em> element
in italic.
# **Quotations**
- \<blockquote>  
The \<blockquote> element is
used for longer quotes that take
up an entire paragraph. Note
how the \<p> element is still
used inside the \<blockquote>
element.
Browsers tend to indent the
contents of the \<blockquote>
element, however you should not
use this element just to indent a
piece of text — rather you should
achieve this effect using CSS. 
- \<q>  
The \<q> element is used for
shorter quotes that sit within
a paragraph. Browsers are
supposed to put quotes around
the \<q> element, however
Internet Explorer does not —
therefore many people avoid
using the \<q> element.
# **Introducing CSS**  
- CSS allows you to create rules that specify how the content of an element should appear. For example, you can specify that
the background of the page is cream, all paragraphs should
appear in gray using the Arial typeface, or that all level one
headings should be in a blue, italic, Times typeface.
Once you have learned how to write a CSS rule, learning CSS
mostly involves learning the different properties you can use.
So this chapter will:
+ Introduce you to how CSS works
+ Teach you how to write CSS rules
+ Show you how CSS rules apply to HTML pages.  
_The remaining chapters in this section will look at all of the
various CSS properties you can use._ 
# Using External CSS
- \<link>  
The \<link> element can be used
in an HTML document to tell the
browser where to find the CSS
file used to style the page. It is an
empty element (meaning it does
not need a closing tag), and it
lives inside the /<head> element.
It should use three attributes:  
**href**  
This specifies the path to the
CSS file (which is often placed in
a folder called css or styles).  
**type**  
This attribute specifies the type
of document being linked to. The
value should be text/css.  
**rel**  
This specifies the relationship
between the HTML page and
the file it is linked to. The value
should be stylesheet when
linking to a CSS file.
# **STATEMENTS in JS**
A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.
Statements should end with a semicolon.  
# **COMMENTS IN JS**
You should write comments to explain what your code does.
They help make your code easier to read and understand.
This can help you and others who read your code. 
# **WHAT IS A VARIABLE?**
A script will have to temporarily
store the bits of information it
needs to do its job. It can store this
data in variables. 
# **HOW TO USE A VARIABLE TO STORE A NUMBER ?**
> Here, three variables are created
and values are assigned to them.  
> - price holds the price of an
individual tile
> - quantity holds the number
of tiles a customer wants
> - to ta 1 holds the total cost of
the tiles  
Note that the numbers are not
written inside quotation marks.
Once a value has been assigned
to a variable, you can use the
variable name to represent that
value (much like you might have
done in algebra). Here, the total
cost is calculated by multiplying
the price of a single tile by the
number of tiles the customer
wants.
The result is then written into
the page on the final two lines.
You see this technique in more
detail on p194 and p216.
The first of these two lines finds
the element whose id attribute
has a value of cost, and the final
line replaces the content of that
element with new content.
Note: There are many ways to
write content into a page, and
several places you can place
your script. The advantages and
disadvantages of each technique
are discussed on p226. This
technique will not work in IE8.
 
