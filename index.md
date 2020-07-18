# HTML5 Test page

This is a test page filled with common HTML elements to be used to provide visual feedback whilst building CSS systems and frameworks.
- [Text](#text)
  - [Headings](#headings)
  - [Paragraphs](#paragraphs)
  - [Blockquotes](#blockquotes)
  - [Lists](#lists)
  - [Horizontal rules](#horizontal-rules)
  - [Tabular data](#tabular-data)
  - [Code](#code)
  - [Inline elements](#inline-elements)
  - [HTML Comments](#html-comments)
- [Embedded content](#embedded-content)
  - [Images](#images)
  - [Audio](#audio)
  - [Video](#video)
  - [Canvas](#canvas)
  - [Meter](#meter)
  - [Progress](#progress)
  - [Inline SVG](#inline-svg)
  - [IFrames](#iframes)
- [Form Elements](#form-elements)
  - [Input fields](#input-fields)
  - [Select menus](#select-menus)
  - [Checkboxes](#checkboxes)
  - [Radio buttons](#radio-buttons)
  - [Textareas](#textareas)
  - [HTML5 inputs](#html5-inputs)
  - [Action buttons](#action-buttons)

## Text

### Headings

## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

[[Top]](#html5-test-page)

### Paragraphs
A paragraph (from the Greek paragraphos, “to write beside” or “written beside”) is a self-contained unit of a discourse in writing dealing with a particular point or idea. A paragraph consists of one or more sentences. Though not required by the syntax of any language, paragraphs are usually an expected part of formal writing, used to organize longer prose.

[[Top]](#html5-test-page)

### Blockquotes
> A block quotation (also known as a long quotation or extract) is a quotation in a written document, that is set off from the main text as a paragraph, or block of text.
> It is typically distinguished visually using indentation and a different typeface or smaller size quotation. It may or may not include a citation, usually placed at the bottom.
> – Said no one, ever.

[[Top]](#html5-test-page)

### Lists

#### Definition list
Definition List Title
: This is a definition list division. If you see a colon, the markdown processor doesn't support this feature.

#### Ordered List
1. List Item 1
2. List Item 2
3. List Item 3
   
#### Unordered List
- List Item 1
- List Item 2
- List Item 3

[[Top]](#html5-test-page)

### Horizontal rules

---

[[Top]](#html5-test-page)

            <header><h3>Tabular data</h3></header>
            <table>
              <caption>Table Caption</caption>
              <thead>
                <tr>
                  <th>Table Heading 1</th>
                  <th>Table Heading 2</th>
                  <th>Table Heading 3</th>
                  <th>Table Heading 4</th>
                  <th>Table Heading 5</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td>Table Cell 1</td>
                  <td>Table Cell 2</td>
                  <td>Table Cell 3</td>
                  <td>Table Cell 4</td>
                  <td>Table Cell 5</td>
                </tr>
                <tr>
                  <td>Table Cell 1</td>
                  <td>Table Cell 2</td>
                  <td>Table Cell 3</td>
                  <td>Table Cell 4</td>
                  <td>Table Cell 5</td>
                </tr>
                <tr>
                  <td>Table Cell 1</td>
                  <td>Table Cell 2</td>
                  <td>Table Cell 3</td>
                  <td>Table Cell 4</td>
                  <td>Table Cell 5</td>
                </tr>
                <tr>
                  <td>Table Cell 1</td>
                  <td>Table Cell 2</td>
                  <td>Table Cell 3</td>
                  <td>Table Cell 4</td>
                  <td>Table Cell 5</td>
                </tr>
              </tbody>
              <tfoot>
                <tr>
                  <th>Table Footer 1</th>
                  <th>Table Footer 2</th>
                  <th>Table Footer 3</th>
                  <th>Table Footer 4</th>
                  <th>Table Footer 5</th>
                </tr>
              </tfoot>
            </table>
            <footer><p><a href="#top">[Top]</a></p></footer>
          </article>
          <article id="text__code">
            <header><h3>Code</h3></header>
            <div>
              <p><strong>Keyboard input:</strong> <kbd>Cmd</kbd></p>
              <p><strong>Inline code:</strong> <code>&lt;div&gt;code&lt;/div&gt;</code></p>
              <p><strong>Sample output:</strong> <samp>This is sample output from a computer program.</samp></p>
              <h2>Pre-formatted text</h2>
              <pre>P R E F O R M A T T E D T E X T
  ! " # $ % &amp; ' ( ) * + , - . /
  0 1 2 3 4 5 6 7 8 9 : ; &lt; = &gt; ?
  @ A B C D E F G H I J K L M N O
  P Q R S T U V W X Y Z [ \ ] ^ _
  ` a b c d e f g h i j k l m n o
  p q r s t u v w x y z { | } ~ </pre>
            </div>
            <footer><p><a href="#top">[Top]</a></p></footer>
          </article>
          <article id="text__inline">
            <header><h3>Inline elements</h3></header>
            <div>
              <p><a href="#!">This is a text link</a>.</p>
              <p><strong>Strong is used to indicate strong importance.</strong></p>
              <p><em>This text has added emphasis.</em></p>
              <p>The <b>b element</b> is stylistically different text from normal text, without any special importance.</p>
              <p>The <i>i element</i> is text that is offset from the normal text.</p>
              <p>The <u>u element</u> is text with an unarticulated, though explicitly rendered, non-textual annotation.</p>
              <p><del>This text is deleted</del> and <ins>This text is inserted</ins>.</p>
              <p><s>This text has a strikethrough</s>.</p>
              <p>Superscript<sup>®</sup>.</p>
              <p>Subscript for things like H<sub>2</sub>O.</p>
              <p><small>This small text is small for for fine print, etc.</small></p>
              <p>Abbreviation: <abbr title="HyperText Markup Language">HTML</abbr></p>
              <p><q cite="https://developer.mozilla.org/en-US/docs/HTML/Element/q">This text is a short inline quotation.</q></p>
              <p><cite>This is a citation.</cite></p>
              <p>The <dfn>dfn element</dfn> indicates a definition.</p>
              <p>The <mark>mark element</mark> indicates a highlight.</p>
              <p>The <var>variable element</var>, such as <var>x</var> = <var>y</var>.</p>
              <p>The time element: <time datetime="2013-04-06T12:32+00:00">2 weeks ago</time></p>
            </div>
            <footer><p><a href="#top">[Top]</a></p></footer>
          </article>
          <article id="text__comments">
            <header><h3>HTML Comments</h3></header>
            <div>
              <p>There is comment here: <!--This comment should not be displayed--></p>
              <p>There is a comment spanning multiple tags and lines below here.</p>
              <!--<p><a href="#!">This is a text link. But it should not be displayed in a comment</a>.</p>
              <p><strong>Strong is used to indicate strong importance. But, it should not be displayed in a comment</strong></p>
              <p><em>This text has added emphasis. But, it should not be displayed in a comment</em></p>-->
            </div>
            <footer><p><a href="#top">[Top]</a></p></footer>
          </article>
        </section>
        <section id="embedded">
          <header><h2>Embedded content</h2></header>
          <article id="embedded__images">
            <header><h3>Images</h3></header>
            <div>
              <h4>No <code>&lt;figure&gt;</code> element</h4>
              <p><img src="https://placekitten.com/480/480" alt="Image alt text"></p>
              <h4>Wrapped in a <code>&lt;figure&gt;</code> element, no <code>&lt;figcaption&gt;</code></h4>
              <figure><img src="https://placekitten.com/420/420" alt="Image alt text"></figure>
              <h4>Wrapped in a <code>&lt;figure&gt;</code> element, with a <code>&lt;figcaption&gt;</code></h4>
              <figure>
                <img src="https://placekitten.com/420/420" alt="Image alt text">
                <figcaption>Here is a caption for this image.</figcaption>
              </figure>
            </div>
            <footer><p><a href="#top">[Top]</a></p></footer>
          </article>
          <article id="embedded__audio">
            <header><h3>Audio</h3></header>
            <div><audio controls="">audio</audio></div>
            <footer><p><a href="#top">[Top]</a></p></footer>
          </article>
          <article id="embedded__video">
            <header><h3>Video</h3></header>
            <div><video controls="">video</video></div>
            <footer><p><a href="#top">[Top]</a></p></footer>
          </article>
          <article id="embedded__canvas">
            <header><h3>Canvas</h3></header>
            <div><canvas>canvas</canvas></div>
            <footer><p><a href="#top">[Top]</a></p></footer>
          </article>
          <article id="embedded__meter">
            <header><h3>Meter</h3></header>
            <div><meter value="2" min="0" max="10">2 out of 10</meter></div>
            <footer><p><a href="#top">[Top]</a></p></footer>
          </article>
          <article id="embedded__progress">
            <header><h3>Progress</h3></header>
            <div><progress>progress</progress></div>
            <footer><p><a href="#top">[Top]</a></p></footer>
          </article>
          <article id="embedded__svg">
            <header><h3>Inline SVG</h3></header>
            <div><svg width="100px" height="100px"><circle cx="100" cy="100" r="100" fill="#1fa3ec"></circle></svg></div>
            <footer><p><a href="#top">[Top]</a></p></footer>
          </article>
          <article id="embedded__iframe">
            <header><h3>IFrame</h3></header>
            <div><iframe src="index.html" height="300"></iframe></div>
            <footer><p><a href="#top">[Top]</a></p></footer>
          </article>
        </section>
        <section id="forms">
          <header><h2>Form elements</h2></header>
          <form>
            <fieldset id="forms__input">
              <legend>Input fields</legend>
              <p>
                <label for="input__text">Text Input</label>
                <input id="input__text" type="text" placeholder="Text Input">
              </p>
              <p>
                <label for="input__password">Password</label>
                <input id="input__password" type="password" placeholder="Type your Password">
              </p>
              <p>
                <label for="input__webaddress">Web Address</label>
                <input id="input__webaddress" type="url" placeholder="http://yoursite.com">
              </p>
              <p>
                <label for="input__emailaddress">Email Address</label>
                <input id="input__emailaddress" type="email" placeholder="name@email.com">
              </p>
              <p>
                <label for="input__phone">Phone Number</label>
                <input id="input__phone" type="tel" placeholder="(999) 999-9999">
              </p>
              <p>
                <label for="input__search">Search</label>
                <input id="input__search" type="search" placeholder="Enter Search Term">
              </p>
              <p>
                <label for="input__text2">Number Input</label>
                <input id="input__text2" type="number" placeholder="Enter a Number">
              </p>
              <p>
                <label for="input__text3" class="error">Error</label>
                <input id="input__text3" class="is-error" type="text" placeholder="Text Input">
              </p>
              <p>
                <label for="input__text4" class="valid">Valid</label>
                <input id="input__text4" class="is-valid" type="text" placeholder="Text Input">
              </p>
            </fieldset>
            <p><a href="#top">[Top]</a></p>
            <fieldset id="forms__select">
              <legend>Select menus</legend>
              <p>
                <label for="select">Select</label>
                <select id="select">
                  <optgroup label="Option Group">
                    <option>Option One</option>
                    <option>Option Two</option>
                    <option>Option Three</option>
                  </optgroup>
                </select>
              </p>
            </fieldset>
            <p><a href="#top">[Top]</a></p>
            <fieldset id="forms__checkbox">
              <legend>Checkboxes</legend>
              <ul class="list list--bare">
                <li><label for="checkbox1"><input id="checkbox1" name="checkbox" type="checkbox" checked="checked"> Choice A</label></li>
                <li><label for="checkbox2"><input id="checkbox2" name="checkbox" type="checkbox"> Choice B</label></li>
                <li><label for="checkbox3"><input id="checkbox3" name="checkbox" type="checkbox"> Choice C</label></li>
              </ul>
            </fieldset>
            <p><a href="#top">[Top]</a></p>
            <fieldset id="forms__radio">
              <legend>Radio buttons</legend>
              <ul class="list list--bare">
                <li><label for="radio1"><input id="radio1" name="radio" type="radio" class="radio" checked="checked"> Option 1</label></li>
                <li><label for="radio2"><input id="radio2" name="radio" type="radio" class="radio"> Option 2</label></li>
                <li><label for="radio3"><input id="radio3" name="radio" type="radio" class="radio"> Option 3</label></li>
              </ul>
            </fieldset>
            <p><a href="#top">[Top]</a></p>
            <fieldset id="forms__textareas">
              <legend>Textareas</legend>
              <p>
                <label for="textarea">Textarea</label>
                <textarea id="textarea" rows="8" cols="48" placeholder="Enter your message here"></textarea>
              </p>
            </fieldset>
            <p><a href="#top">[Top]</a></p>
            <fieldset id="forms__html5">
              <legend>HTML5 inputs</legend>
              <p>
                <label for="ic">Color input</label>
                <input type="color" id="ic" value="#000000">
              </p>
              <p>
                <label for="in">Number input</label>
                <input type="number" id="in" min="0" max="10" value="5">
              </p>
              <p>
                <label for="ir">Range input</label>
                <input type="range" id="ir" value="10">
              </p>
              <p>
                <label for="idd">Date input</label>
                <input type="date" id="idd" value="1970-01-01">
              </p>
              <p>
                <label for="idm">Month input</label>
                <input type="month" id="idm" value="1970-01">
              </p>
              <p>
                <label for="idw">Week input</label>
                <input type="week" id="idw" value="1970-W01">
              </p>
              <p>
                <label for="idtl">Datetime-local input</label>
                <input type="datetime-local" id="idtl" value="1970-01-01T00:00">
              </p>
            </fieldset>
            <p><a href="#top">[Top]</a></p>
            <fieldset id="forms__action">
              <legend>Action buttons</legend>
              <p>
                <input type="submit" value="<input type=submit>">
                <input type="button" value="<input type=button>">
                <input type="reset" value="<input type=reset>">
                <input type="submit" value="<input disabled>" disabled>
              </p>
              <p>
                <button type="submit">&lt;button type=submit&gt;</button>
                <button type="button">&lt;button type=button&gt;</button>
                <button type="reset">&lt;button type=reset&gt;</button>
                <button type="button" disabled>&lt;button disabled&gt;</button>
              </p>
            </fieldset>
            <p><a href="#top">[Top]</a></p>
          </form>
        </section>
      </main>
      <footer>
        <p>Code on <a href="https://github.com/rockorager/html5-test-page-validated">GitHub</a>.</p>
      </footer>
    </div>
  </body>
</html>