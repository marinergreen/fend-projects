You've learned a lot about web development so far. I want you to take a moment to write down your thoughts about web development here. Answer the following questions:
  * What new skills have you learned?
  * What has been easy?
  * What has been difficult?
  * How have you used the problem solving strategies from the first project to overcome challenges so far?

---

One thing I learned is the importance of using semantic markup.
For example, the <i> and <b> tags should no longer be used just to
make text italicised and bold, respectively. Rather, the <emphasis> and
<strong> tags are preferred because they convey semantic meaning.
Another example is wrapping an <image> and its <p> caption with
<figure> and <figcaption>.


A couple things have been easy. A lot of tags like <h1>, <p>, <img>, <a>
are very straighforward and I know when to use them. Knowing that HTML 
tags are nested in a tree structure and making sure there are no blatant
syntax errors is easy thanks to the editor I'm using.


One thing that has been difficult is deciding which tags to use when there
may be multiple options. I try to be semantic, but sometimes the result isn't
quite what I was expecting. For example:

 * Should I use <blockquote>? Oh wait, that indents the entire paragraph, 
   so nevermind I'll just go with <p>.
 * Should I use <em> or <i>? I decided to go with <i> because I didn't feel
   that semantically the block quote needed emphasis and was more in line with
   what MDN mentions regarding <i>: "...the <i> tag represents text that is 
   set off from the normal prose, such as the name of a movie or book, a foreign
   word...".
 * Should I break up long links for readability? But then the W3C Validator
   complains of an error. I was torn and decided to please the W3C Validator.
   But in future situations I'll probably go for readibility.


Other than being occasionally torn about what tags to use I thankfully I haven't
gotten too stuck yet. MDN has been a terrific resource.
