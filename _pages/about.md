---
   title: About
   permalink: /about
---

# {{ page.title }}

Welcome to your wiki!

This theme was heavily inspired by worldbuilding websites such as [WorldAnvil](https://www.worldanvil.com/) and [Notebook.ai](https://www.notebook.ai/), both of which allow you to store articles and data in a wide variety of categories. I think both of those websites are fantastic, but not exactly what I was looking for, and so I never got as much use out of either of them as I hoped I would. I also tried out Tiddlywiki for a time, which was closer to what I wanted but still not as customizable as I would like. All of these websites I found a little too cluttered for my taste, whereas we're all familiar with Wikipedia and its layout and functionalities, so I built a Jekyll site that allowed me to recreate that. Hopefully I've succeeded enough for it to be useful to other people!

One of the benefits of a static site generator like Jekyll is privacy - you can serve it locally on your machine and browse it as if it were a fully fledged website, without ever posting anything to the internet. This is an approach I prefer, although you could also easily make it publicly viewable if you wanted (say, via Github Pages). Additionally, it's completely free --- no pricing tiers. You can create whatever categories you like, any time.

## Organizing your wiki

There are a lot of ways to navigate Wikipedia and explore its contents. I'm sure many people have never even been to the [contents page](https://en.wikipedia.org/wiki/Wikipedia:Contents), but it lists several different methods of interacting with the site's contents: lists, outlines, overviews, glossaries, portals, categories, indices. Personally I like the concept of portals; have a look at [this one](https://en.wikipedia.org/wiki/Portal:Wine), for example, a kind of busy hub for all things relating to a given subject, with links to the other forms of navigations. You can organize your wiki however you want, but I chose to divide things up into very high level subject distinctions. I didn't want to replicate Wikipedia's exact categories, though, because I didn't want to recreate any of its assumptions, either: for example, the idea that people and culture can be clearly separated from each other, or that arts and sciences and technologies are subjects that can be neatly separated from each other.

Here's the extremely broad list I came up with:
1. Geography: this one is hard to sum up in a single word, but it's a pretty intuitive natural category --- the physical world, covering physical geography of the planet, landforms and water bodies and the processes that form them, climate, biomes and ecoregions, meteorology and oceanography
2. Biology: also pretty intuitive, the evolution of life on the planet, the different types of lifeforms, and the relationships between them
3. People: this one is much more nebulous, and all the remaining categories are really just very large subcategories of this one.
4. Languages
5. Places
6. Activities
7. Events
8. Figures
9. Items
10. Phenomena
11. Infrastructure
12. WIPs










---

## plugin testing

### DefineLanguageTag ✅
{ lang "ko" "바이 괕 모" "iced jelly dish" %}

### RenderPhoneticTag ✅
{% ipa /phonemic text/ %} more text

{% ipa [phonetic text] %} more text

### GrammaticalCategoryLabel
{ gcl erg "ergative case" %}-{ gcl fut "future tense" %}-{ gcl neg "negative" %}

### InterlinearGlossFilter
{ interlinear %}
   { gloss sentence in object lang %}
   { gloss sentence in object lang broken down into morphemes %}
   { gloss interlinear gloss of morphemes %}
   { gloss translation into target lang %}
{ endinterlinear %}

{ interlinear 'gila aburun ferma hamišaluǧ güǧüna amuqʼdač' %}
   gila abur-u-n ferma hamišaluǧ güǧüna amuqʼ-da-č
   now they-OBL-GEN farm forever behind stay-FUT-NEG
   Now their farm will not stay behind forever.
{ endinterlinear %}

<table>
   <tr>
      <td colspan="6">Gila aburun ferma hamišaluǧ güǧüna amuqʼdač</td>
   </tr>
   <tr>
      <td>gila</td>
      <td>abur-u-n</td>
      <td>ferma</td>
      <td>hamišaluǧ</td>
      <td>güǧüna</td>
      <td>amuqʼ-da-č</td>
   </tr>
   <tr>
      <td>now</td>
      <td>they-OBL-GEN</td>
      <td>farm</td>
      <td>forever</td>
      <td>behind</td>
      <td>stay-FUT-NEG</td>
   </tr>
   <tr>
      <td colspan="6">Now their farm will not stay behind forever.</td>
   </tr>
</table>

### InterlinearGlossTag
{ gloss text to be glossed here %}

### RenderBlockquoteTag ✅
{ blockquote "The spectacle before us was indeed sublime." "John Munro" "A Trip to Venus" %}

### RenderMainArticleTag ✅
{ main_article Sample page %}

---

<p>An <code>article</code> defines a self-contained body of content that can stand alone on a page. This is a paragraph within an article. <a href="/wiki/Sample">Here is a link</a> to a sample wiki page.</p>

<section>
   <p>This is a section within an article. This section contains a single paragraph tag with multiple lines of text.</p>

   <p>a æ ɑ ɒ ɐ b ɓ β ʙ c ç d ɖ ɗ e ɘ ɛ ɜ ɞ ə f ɸ g ɡ ɠ ɢ ʛ ɰ h ɦ ħ ɧ ɥ ʜ i ɨ ɪ j ʝ ɟ ʄ k l ɫ ɬ ɮ ɭ ʟ m ɱ n ɳ ɲ ŋ ɴ o ø ɵ ɔ œ ɶ p q r ɹ ɾ ɽ ɻ ɺ ʁ ʀ s ʂ ɕ ʃ t ʈ u ʉ ʊ ɯ ʌ v ⱱ ʋ w ʍ x ɣ χ y ʏ ʎ z ʐ ʑ ʒ θ ð ʔ ʡ ʕ ʢ ʘ ǀ ǃ ǂ ǁ</p>

   <p>Diacritics: e̟ e̘ e̺ e̤ ë e̪ e̯ ĕ e̻ e̼ e̞ e̽ ẽ e̝ e̠ e̙ e˞ e̜ e̹ e̩ t͡s e̚ ḛ e̬ e̥ ˈ ˌ ː ˑ ʰ ʷ ˡ ⁿ ʲ ˤ ˠ ˥ ˦ ˧ ˨ ˩</p>
</section>

<section>
   <h2>paragraphs</h2>

   <p>A paragraph (from the Greek paragraphos, “to write beside” or “written beside”) is a self-contained unit of a discourse in writing dealing with a particular point or idea. A paragraph consists of one or more sentences. Though not required by the syntax of any language, paragraphs are usually an expected part of formal writing, used to organize longer prose.</p>
</section>

<section>
   <h2>blockquotes</h2>

   <figure>
      <blockquote cite="http://">
         <p>A block quotation (also known as a long quotation or extract) is a quotation in a written document, that is set off from the main text as a paragraph, or block of text.</p>

         <p>It is typically distinguished visually using indentation and a different typeface or smaller size quotation. It may or may not include a citation, usually placed at the bottom.</p>

         <figcaption>
            Author, <cite>Work</cite>
         </figcaption>
      </blockquote>
   </figure>

</section>

<section>
   <h2>lists</h2>

   <h3>definition list</h3>

   <dl>
      <dt>term</dt>
      <dd>definition</dd>

      <dt>term</dt>
      <dd>definition</dd>
   </dl>

   <h3>ordered list</h3>

   <ol>
      <li>list item</li>
      <li>list item</li>
      <li>list item</li>
   </ol>

   <h3>unordered list</h3>

   <ul>
      <li>list item</li>
      <li>list item</li>
      <li>list item</li>
   </ul>

</section>

<section>
   <h2>horizontal rule</h2>

   A paragraph (from the Greek paragraphos, “to write beside” or “written beside”) is a self-contained unit of a discourse in writing dealing with a particular point or idea. A paragraph consists of one or more sentences. Though not required by the syntax of any language, paragraphs are usually an expected part of formal writing, used to organize longer prose.

   <hr>

   A paragraph (from the Greek paragraphos, “to write beside” or “written beside”) is a self-contained unit of a discourse in writing dealing with a particular point or idea. A paragraph consists of one or more sentences. Though not required by the syntax of any language, paragraphs are usually an expected part of formal writing, used to organize longer prose.

</section>

<section>
   <h2>tabular data</h2>

   <table>
      <caption>table caption</caption>
      <thead>
         <tr>
            <th>table heading</th>
            <th>table heading</th>
            <th>table heading</th>
            <th>table heading</th>
            <th>table heading</th>
         </tr>
      </thead>
      <tbody>
         <tr>
            <td>table data</td>
            <td>table data</td>
            <td>table data</td>
            <td>table data</td>
            <td>table data</td>
         </tr>
         <tr>
            <td>table data</td>
            <td>table data</td>
            <td>table data</td>
            <td>table data</td>
            <td>table data</td>
         </tr>
         <tr>
            <td>table data</td>
            <td>table data</td>
            <td>table data</td>
            <td>table data</td>
            <td>table data</td>
         </tr>
      </tbody>
   </table>

</section>

<section>
   <h2>code</h2>

   <p>Keyboard input: <kbd>Cmd</kbd></p>
   <p>Inline code: <code>&lt;div&gt;code&lt;/div&gt;</code></p>
   <p>Sample output: <samp>This is sample output from a computer program.</samp></p>

   <h3>pre-formatted text</h3>

   <pre>$ gem bundle install</pre>

</section>

<section>
   <h2>inline elements</h2>

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
   <p>Abbreviation: <abbr title="HyperText Markup Language">HTML</abbr></p>
   <p><q cite="https://developer.mozilla.org/en-US/docs/HTML/Element/q">This text is a short inline quotation.</q></p>
   <p><cite>This is a citation.</cite></p>
   <p>The <dfn>dfn element</dfn> indicates a definition.</p>
   <p>The <mark>mark element</mark> indicates a highlight.</p>
   <p>The <var>variable element</var>, such as <var>x</var> = <var>y</var>.</p>
   <p>The time element: <time datetime="2013-04-06T12:32+00:00">2 weeks ago</time></p>
   <p><small>This small text is small for for fine print, etc.</small></p>

</section>

<!--Commented out for shorter loading time lol-------

<section>
   <h2>images</h2>

   <h3>No <code>&lt;figure&gt;</code> element</h3>
   <p><img src="https://source.unsplash.com/random/1000x600" alt="Image alt text" width="750" height="400"></p>

   <h3>Wrapped in a <code>&lt;figure&gt;</code> element, no <code>&lt;figcaption&gt;</code></h3>
   <figure><img src="https://source.unsplash.com/random/600x400?sig=1" alt="Image alt text" width="600" height="400"></figure>

   <h3>Wrapped in a <code>&lt;figure&gt;</code> element, with a <code>&lt;figcaption&gt;</code></h3>
   <figure>
      <img src="https://source.unsplash.com/random/600x800?sig=2" alt="Image alt text" width="600" height="800">
      <figcaption>Here is a caption for this image.</figcaption>
   </figure>

</section>

<section>
   <h2>forms</h2>

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
            <input id="input__webaddress" type="url" placeholder="https://example.com">
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

      <fieldset id="forms__checkbox">
         <legend>Checkboxes</legend>
         <ul class="list list--bare">
            <li><label for="checkbox1"><input id="checkbox1" name="checkbox" type="checkbox" checked="checked"> Choice
            A</label></li>
            <li><label for="checkbox2"><input id="checkbox2" name="checkbox" type="checkbox"> Choice B</label></li>
            <li><label for="checkbox3"><input id="checkbox3" name="checkbox" type="checkbox"> Choice C</label></li>
         </ul>
      </fieldset>

      <fieldset id="forms__radio">
         <legend>Radio buttons</legend>
         <ul class="list list--bare">
            <li><label for="radio1"><input id="radio1" name="radio" type="radio" class="radio" checked="checked">
            Option 1</label></li>
            <li><label for="radio2"><input id="radio2" name="radio" type="radio" class="radio"> Option 2</label></li>
            <li><label for="radio3"><input id="radio3" name="radio" type="radio" class="radio"> Option 3</label></li>
         </ul>
      </fieldset>

      <fieldset id="forms__textareas">
         <legend>Textareas</legend>
         <p>
            <label for="textarea">Textarea</label>
            <textarea id="textarea" rows="8" cols="48" placeholder="Enter your message here"></textarea>
         </p>
      </fieldset>

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
            <label for="idt">Datetime input</label>
            <input type="datetime" id="idt" value="1970-01-01T00:00:00Z">
         </p>
         <p>
            <label for="idtl">Datetime-local input</label>
            <input type="datetime-local" id="idtl" value="1970-01-01T00:00">
         </p>
      </fieldset>

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

   </form>

</section>

End of comment------------------------------>
