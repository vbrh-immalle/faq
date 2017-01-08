# Curriculum

## Why don’t you have your own curriculum?

Actually most of our curriculum is our own mostly because we try
to keep really relevant and up to date. Often no other material
exists—especially for our target 8-18 age range.  A lot of educational
material also has significant flaws in our view making it more work
to unteach what it requires students to teach.

But also, if something works don't fix it. We look at curriculum
very closely and compare it to our core mission of teaching real
code and tech in ways that professionals use it. We’re also required
to balance this need with that to engage students as young as eight.
CodeCombat.com is a good example of what we see as a perfect balance
of these things. It isn’t perfect, but it is close enough to use
without having to create our own.

## Can I use your curriculum in our school/business/home?

All our materials are released under Open Educational Resources
(OER) with the Creative Commons Attribution-ShareAlike 4.0 (as is included
with them all).

## What curriculum do you follow/recommend?
## Are there any curricula you discourage?

**Codecademy**

Yes, most of the material on codecademy.com is either buggy or out
of date. One best example of this is codecademy.com teaches Python 2,
not Python 3, which was released in 2008. The final 2.7 release was
out in 2010. From the official docs:

> In particular, instructors introducing Python to new programmers
> should consider teaching Python 3 first and then introducing the
> differences in Python 2 afterwards (if necessary), since Python
> 3 eliminates many quirks that can unnecessarily trip up beginning
> programmers trying to learn Python 2.

Codecademy is directly violating this request from the creators of the
language itself and has been for more than five years.

Here is an ongoing list of reported errors that have gone unfixed.
Some of these are rather serious, like those involving semicolon
injection:

*Not HTML5, Using Ancient DHTML/XHTML Instead*

```html
<img href="" />
```

*Semicolon Injection Errors*

Several JavaScript exercises call for putting the bracket on the line
following an `if` statement. Anyone who knows JavaScript knows how bad
this is since it becomes `if (condition);` when interpreted.

```javascript
if (condition)
{
  something
}
```

**CodeCombat.com**

Although CodeCombat.com is a *major* pillar of our program and we
strongly recommend it, using the `loop:` construct, which they added
to simplify the concept of `while True:`, has always annoyed me. I
suggest starting with the loop the way Python really uses it and
telling them what it does right away.

**Code.org**

Great for young kids, even those that cannot type yet, but the
materials are almost entirely focused on dragging and dropping the
right blocks into place instead of typing actual code. We feel this
actually starts young students out nicely, but underestimates the
ability of kids as young at seven to begin typing actual code. Don't
baby them. They can do it.

**Scratch**

Even more focused on entertainment is Scratch. The open-ended
creativity is nice, but their is very little actual programming going
on and certainly nothing students would take with them directly into
a course or job opportunity using real programming methods from the
command line.

**CheckIO.org**

Amazing site, just too darn hard for most students starting out or
between 8 and 18, otherwise great!
 
---
[![home](/assets/home-bw.png)](/README.md)
[![cc-by-sa](/assets/cc-by-sa.png)][cc-by-sa]
[![skilstak](/assets/skilstak-logo-bw.png)][skilstak]
[cc-by-sa]: https://creativecommons.org/licenses/by-sa/4.0/
[skilstak]: http://skilstak.io

