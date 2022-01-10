# Getting Started With Web Development Cheatsheet day-2
### HTML Cheatsheet
This repository contains the cheat sheet for HTML. Fork it and you are good to go 💻 !

## Some Points to be noted:
- <b>HTML</b> : <b>HyperText Markup Language</b>
- We are working with the most recent version of HTML i.e. <b>HTML5</b>
- No such compiler needed. Can work with Notepad or can go for IDE platforms like VSCode, Atom, Sublime, etc.
- Always remember to save your html file with <code>.html</code> and you can open your <code>.html</code> file on any browser.

## Some commonly used HTML tags:
- *!DOCTYPE html* : present at the outermost part of HTML document.
- *&lt;html>.....&lt;/html>* : present at the outermost part of the HTML document if this is used instead of *&lt;!DOCTYPE html>*. 
- *&lt;head>......&lt;/head>* : the head of the document and remains in between the html tags. Contains the title, logo, meta tags, script and style tags.
- *&lt;header>.....&lt;/header>* : mostly written after closing the head tag, i.e. after the head section and before the start of the body section. It is not a necessary tag to be used in your webpage, but can be used for inserting a navigation bar or for anything to display at the top portion of the webpage.
- *&lt;body>.....&lt;/body>* : represents the main body of the webpage. Whatever you want to present in the body of the webpage, you have to write in between the opening and closing tags of the body tag. The body tag also hosts other tags.

### Tags used in between the head tags:
- *&lt;title>......&lt;/title>* : used for giving title to your webpage. The title of the webpage appears in the tab bar of the page when it is opened in the browser. If you don’t specify the title tag, then in the app bar of the browser, (your_filename).html will appear as the title of your webpage.
- *&lt;meta>......&lt;/meta>* : present in between the head tags; helps in making your page responsive and also properly displayable on different devices. It also includes tags for SEO management. If you don’t use it, your webpage will be displayed , but it might not be responsive or SEO-friendly. All well-maintained websites contain meta tags.
- *&lt;script>......&lt;/script>* : in between the head tags, this tag is used for importing external JS packages or external JS code. These tags can also be used for inline JS too. It is not mandatory to use these tags only in the head section; it can be used in the body section too.
- *&lt;style>......&lt;/style>* : in between the head tags, this tag is used for importing external CSS packages or external CSS . These tags can also be used for inline CSS too. It is not mandatory to use these tags only in the head section; it can be used in the body section too.

### Tags used in between the body tags:
<table>
  <tr>
    <th>Tag Name</th>
     <th>Information about the tag</th>
    <th>Inline/Block level element</th>
  </tr>
  <tr>
    <td><i>&lt;section>......&lt;/section></i></td>
    <td>Represents a particular section of the body of your webpage</td>
    <td>Block-level</td>
  </tr>
  <tr>
    <td><i>&lt;article>......&lt;/article></i></td>
    <td>Represents a particular portion of the webpage body. Used for the 'article-type' look.</td>
    <td>Block-level</td>
  </tr>
   <tr>
    <td><i>&lt;p>......&lt;/p></i></td>
    <td>Represents paragraphs in the webpage body.</td>
    <td>Block-level</td>
  </tr>
   <tr>
    <td><i>&lt;span>......&lt;/span></i></td>
    <td>used to focus a particular element in your paragraph, section or article tags. Also used without the before-mentioned tags. </td>
    <td>Inline</td>
  </tr>
  <tr>
    <td><i>&lt;div>......&lt;/div></i></td>
    <td>used to focus a particular 'division' or portion in your webpage. The div tag may contain p,article, section tags and many other tags as well.</td>
    <td>Block-level</td>
  </tr>
  <tr>
    <td><i>&lt;b>......&lt;/b></i></td>
    <td>used for making text <b>bold</b>. Text written in between these two tags will apppear <b>bold</b> in the webpage.</td>
    <td>Inline</td>
  </tr>
  <tr>
    <td><i>&lt;i>......&lt;/i></i></td>
    <td>used for making text <i>italic</i>. Text written in between these two tags will apppear <i>italic</i> in the webpage.</td>
    <td>Inline</td>
  </tr>
  <tr>
    <td><i>&lt;u>......&lt;/u></i></td>
    <td>used for <u>underlining</u> text. Text written in between these two tags will apppear <u>underlined</u> in the webpage.</td>
    <td>Inline</td>
  </tr>
  <tr>
    <td><i>&lt;a href=”(source)” target=”_blank”(if you want the open the page in a new tab or you can leave it blank if you want to show it in the same tab)>......&lt;/a></i></td>
    <td>used to anchor a webpage with another webpage (i.e. forming a passage between the two pages). You can navigate from one page to another with the help of the anchor tag. But the anchor page needs an address and that address is provided by the href within the anchor tag.</td>
    <td>Inline</td>
  </tr>
  <tr>
    <td><i>&lt;img src="(source)" alt="alternative_text">......&lt;/img></i></td>
    <td>can be used with or without its closing tag. Used to include image in your webpage.You specify the image path in the src part.Both height and width specified must have the same units.</td>
    <td>Inline</td>
  </tr>
  <tr>
    <td><i>&lt;br></i></td>
    <td>used for line breaks.</td>
    <td>Block-level</td>
  </tr>
  <tr>
    <td><i>&lt;ul>......&lt;/ul></i></td>
    <td>used for unordered list. The tag used to assign elements in the list as list-items is the <i>&lt;li>......&lt;/li></i> tag.</td>
    <td>Block-level</td>
  </tr>
  <tr>
    <td><i>&lt;ol>......&lt;/ol></i></td>
    <td>used for ordered list. The tag used to assign elements in the list as list-items is the <i>&lt;li>......&lt;/li></i> tag.</td>
    <td>Block-level</td>
  </tr>
  <tr>
    <td> Header tags 
      <ul>
        <li><i>&lt;h1>......&lt;/h1></i></li>
        <li><i>&lt;h2>......&lt;/h2></i></li>
        <li><i>&lt;h3>......&lt;/h3></i></li>
        <li><i>&lt;h4>......&lt;/h4></i></li>
        <li><i>&lt;h5>......&lt;/h5></i></li>
        <li><i>&lt;h6>......&lt;/h6></i></li>
      </ul>
      </td>
    <td>mainly used to represent something as headers or headings.</td>
    <td>Block-level</td>
  </tr>
  <tr>
    <td><i>&lt;sup>......&lt;/sup></i></td>
    <td>used for superscripting a text.</td>
    <td>Inline</td>
  </tr>
  <tr>
    <td><i>&lt;sub>......&lt;/sub></i></td>
    <td>used for subscripting a text.</td>
    <td>Inline</td>
  </tr>
   <tr>
    <td><i>&lt;sub>......&lt;/sub></i></td>
    <td>used for subscripting a text.</td>
    <td>Inline</td>
  </tr>
   <tr>
    <td><i>&lt;table> 
       <br>
      &lt;tr>
      <br>
       &lt;th>......&lt;/th>
       <br>
      &lt;/tr>
       <br>
      &lt;tr>
       <br>
      &lt;td>....&lt;/td>
       <br>
      &lt;/tr>
       <br>
      &lt;/table></i></td>
    <td>HTML table struture</td>
    <td>Block-level</td>
  </tr>
  </table>

### HTML form:
HTML form cheatsheet is provided with example in form.html.
