# Class 4 Reading Notes

In this section for reading notes we will be learning about Structuring web pages with HTML.

## References 

https://careerfoundry.com/en/blog/ux-design/how-to-create-your-first-wireframe/  

https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics 

https://developer.mozilla.org/en-US/docs/Glossary/Semantics

https://developer.mozilla.org/en-US/docs/Web/HTML

https://developer.mozilla.org/en-US/docs/Web/HTML/Element

## Lesson Breakdown 

### Introduction To Wireframing 

#### What Is Wireframe?

Wireframing is a practice used by UX designers which allows them to define and plan the information hierarchy of their design for a website, app, or product. The process focuses on how the designer or client wants the user to process information on a site, based on the user research already performed by the UX design team.

##### Different Wireframe Softwares 

1. Invision 
2. Balsamiq
3. UXPin
4. Wireframe.cc

#### Wireframe Creation Process

Wireframes frawn with paper and a pencil, or at a whiteboard, have the advantage of looking and being very easy to change, which cn help tremendously in early conversations about a website or product.

With the help of paper-prototypes, the user can test with end users at every stage of ideation and design. Changes at these stages are much easier, and therefore cheaper than changes deemed necessary after coding is under way.

Switching later to software after initally hand-drawing your wireframe allows you to keep track of more detailed decisions.

It's likely to be to my advantage to start off hand-drawing my wirefames before executing more detailed versions using an online app or software.

#### Things To Consider 

While everyone can approach wireframing differently from either hand-drawing or using software. More often than not, the decision to use online toold or to wireframe by hand, and the process used to get to from wireframe to code, is less related to the individual preference of the UX Designer, and much more related to what approach the particualr situation requires.

#### Six Steps To Make A Wireframe

1. Do your research 
2.Prepare your research for quick reference 
3. Make sure to have your user flow mapped out
4. Draft, don't draw. Sketch, don't illustrate
5. Add some detail and get testing
6. Start turning your wireframes into prototypes

#### Three Key Priniciples To Make My Wireframe Good

1. Clarity
2.Confidence
3.Simplicity Is Key

### HTML Basics 

#### What Is HTML 

HTML (Hyper Text Markup Lamguage) is the code that is used to structure a web page and its content. HTML consists of a series of elements, which the user uses to enclose, or wrap, different parts of the content to make it appear a certain way, or act a certain way. Enclosing tags can make a word or image hyperlink to somewhere else, italicize words, can make the font bigger or smaller, and so on.

#### Understanding Tags & Elements 

1. The Opening Tag: This consists of the name of the element, wrapped in opening and closing angle brackets "<>" This states where the element begins or starts to take effect.

2. The Closing Tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends. Failing to add a closing tag is one of the standard beginner errors and can lead to strange results.

3. The Content: This is the content of the element, for example with a paragraph tag this would be the text inside of the tags.

4. The Element: The opening tag, the closing tag, and the content together comprise the element.

Elements can also have attributes. Attributes contain extra information about the element that the use doesnt want to appear in the actual content.  

Attributes that set a value always have:

1. A space between it and the element name( or the previous attribute, if the element already has one or more attributes).

2. The attribute name followed by an equal sign.  

3. The attribute value wrapped by opening and closing quotation marks.  

#### Nesting Elements  

The user can put elements inside other elements, this is called nesting. For example if the user wanted to state that our cat is very grumpy, the user could wrap the word "very" in a <strong> element, which means that the word is to be strongly emphasized.

#### Anatomy Of An HTML Document 

1. DOCTYPE html- Main job is to make sure the document behaves correctly.

2. HTML Element - This element wraps all the content on the entire page and is sometimes known as the root element. It also includes the lang attribute, setting the primary language of the document.

3. Head Element - This element acts as  a container for all the stuff you want to include on the HTML page that isn't the content you are showing to your page's viewers. This includes things like keywords and a page description that you want to appear in searxh results, CSS to style our content, character set declarations, and more.  

4. Meta charset="utf-8" This element sets the character set your document should use to UTF-8 which includes most characters from the vast majority of written languages. Essentially, it can now handle any textual content you might put on it. There is no reason not to set this, and it can help avoid some problems later on.

5. Meta name="viewport" content="width=device-width" - This viewport element ensures the page renders at the width of the viewport, preventing mobile browsers from rendering pages wider than the viewport and then shrinking them down.

6. The title element sets the title of the user page, which is the title that appears in the browser tab the page is loaded in. It is also used to describe the page when a user bookmark/favorite it. 

7. The body element contains all the content that the user would want to show to web users when they visit the user webpage, whether that's text, images,videos, games, playable audio tracks, or whatever else.

The <img> element embeds an image into the user web page in the position it appears. This is done via the src (source) attribute, which contains the path to the image file.

The alt (alternative) attribute the user can specify descriptive text for users who cannot see the image.

#### Marking Up Text

Headings - Heading elements allows the user to specify that certain parts of the users content are headings, or subheadings. HTML contains 6 heading levels, h1 - h6

Paragraphs - The <p> elements are for containing paragraphs of text; I will use these frequently when marking up regualar text content.

Lists: Unordered lists and ordered lists.

1. Unordered lists are for lists where the order of the items doesn't matter, such as a shopping list. These are wrapped in an <ul> element.

2. Ordered lists are for lists where the order of the items does matter, such as a recipe. These are wrapped in an <ol> element.

Each item inside the lists is put inside an <li> (list item) element.

#### Links

Links are very important, they are what makes the web a web! For a user to add a link, they need to use the <a> which is short form for anchor.

### Semantics  

In programming, Semantics refers to the meaning of a piece of code. For example in HTML, the h1 element is a semantic element, which gives the text it wraps around the role(or meaninng) of "a top level heading on your page."


#### Some Of The Benefits Of Writing Semantic Markup

1. Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)

2. Screen readers can use it as a signpost to help visually impaired users navigate a page

3. Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes

4. Suggests to the developer the type of data that will be populated

5. Semantic naming mirrors proper custom element/component naming

There are roughly 100 semantic elements available.

### Thing I Want To Know More About

1. New elements to make learning code easier. 
