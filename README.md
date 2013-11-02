javascript-best-practice
========================

A collection of JavaScript Best Practices

![Fit vs Fat](https://raw.github.com/nelsonic/javascript-best-practice/master/images/fit-vs-fat.jpg "Fit vs Fat")

Much like being in shape, 
writing *consistent*, *maintainable* and *performant* code
does not have to be "*aspiration*", its a *decision* we make
and stick to. If you see someone writing junk, share this with them! 


### Short List

1. *Use* the “**Good Parts**” (and *avoid* the “*Bad parts*”)
2. **Clear**, **Concise** and **Commented** Code
3. **Meaningful Variable Names** (Especially as Parameters)
4. *Avoid* **Global** Variables
5. Use **JSLint** to ensure your code is consistent.
6. *Always* **Unit Test** your Code (even for simple/quick fixes and one-liners)
7. *Learn* (“Real”/”Raw”) JavaScript (fundamentals) before using Libraries like JQuery/Backbone
8. Avoid Libraries/Modules/Frameworks until you *understand* them. especially when they are un-tested/documented if(tests===false) alert(“Don’t use it!”) … 
9. **Never Commit**/Ship **Broken**/Buggy **Code** even when “PMs” Pressure You!
10. Its only “**Done**” when its “**Documented**”.

### Extra Mile

11. Learn **CoffeeScript** it will Set you Free!
12. Learn & Use **Patterns**
13. (Don’t be afraid to) *Critique* someone else’s code if they ignore any coding best practices (by pointing to the *specific* “guideline” that is not being followed)
14. Compile your code with **Source Maps** (to aid debugging)




My ambition is to write a *system* that lints JavaScript code during build
and rejects code that does not adhere to these best practices.

### Recommended Reading

![Best Teachers](https://pbs.twimg.com/media/BIOLrIVCIAA7NJG.jpg:medium "Best Teachers")

Completely New to JavaScript? Welcome! Start with this book:

- **Dom Scripting**: Web Design with JavaScript and the Document Object Model - 
www.amazon.com/dp/B004VH7LQE  *BUY IT*! Invest in knowing how to build the future! 
(if you cannot afford the $18 for a secondhand “like new” copy, get in touch, 
I will lend it to you!) 

If you’ve already written a bit of JS and not read “The Good Parts” start there.

- JavaScript **The Good Parts** (Douglas Crockford 2008): 
http://www.amazon.com/dp/0596517742

Once you have mastered the **Good Parts**, *hone* your **craft**:

- JavaScript **Patterns** (Stoyan Stefanov 2010): 
http://www.amazon.com/dp/0596806752/

- **High Performance** JavaScript (Nicholas C. Zakas 2010):
http://www.amazon.com/dp/059680279X/


While I'm a **strong advocate** of **learning by doing**, 
*sometimes* it pays to learn from the knowledge/mistakes of
more experienced people by reading the books they have written...

I keep a *small stack* of the best titles on my desk to recommend to my
"*junior*" developers:

![Stack of JavaScript Books](https://pbs.twimg.com/media/BHfMcdNCEAAFuj0.jpg "Do your Homework")

If you live in London and can't afford to buy books, message me on 
[LinkedIn](http://uk.linkedin.com/in/nelsonic),
I'm happy to *give* you any of my books in exchange for *insights*. :-)


### Notes

#### Sources

- http://www.w3.org/wiki/JavaScript_best_practices 
- https://github.com/stevekwan/best-practices/blob/master/javascript/best-practices.md
- http://www.developerdrive.com/2011/08/top-10-must-follow-javascript-best-practices-2/
- http://www.codeproject.com/Articles/580165/JavaScript-Best-Practice
- http://www.javascripttoolbox.com/bestpractices/
- http://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml 
- http://net.tutsplus.com/tutorials/javascript-ajax/24-javascript-best-practices-for-beginners/



### History

This originally started out in a Google Doc:
https://docs.google.com/document/d/1t9msoVNY5KlRnHeIAgUgqDyaXh2Q35v5zHtdpZ2vy-U
I created it to share/suggest best practices with my team of developers.
The idea was that all developers in the company could edit the doc and a 
generally agreed code for writing code could be established.

The *reality* was that I was the only one who even *looked* at the Google Doc!
Nobody made any comments or contributions. :-(
*Too "Busy"* coding to stop and think: "*Is my code consistent...?*" or 
"*Is this maintainable by someone else?*" ... This is not the time or place 
to voice my *frustration* at trying to get people in an established 
organisation (with more **bad habits** than you can *imagine*) to adopt 
industry best practices for JavaScript code. 
Each to their own. 

Its time to put this up on GitHub for a wider audience to access. ;-)