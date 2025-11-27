# frontEnd_html

[Exercises](https://www.freecodecamp.org/learn/2022/responsive-web-design/learn-html-by-building-a-cat-photo-app/step-2?messages=success%5B0%5D%3Dflash.signin-success)

[Cheat sheet](https://web.stanford.edu/group/csp/cs21/htmlcheatsheet.pdf)

[Basic:](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Basic_HTML_syntax)


## Basic

- **Enclosing:**  
```html
<p>My cat is very grumpy</p>
```

- **Nesting elements:**  
```html
<p>My cat is <strong>very</strong> grumpy.</p>
```

- **Void elements:**  
```html
<img src="https://raw.githubusercontent.com/mdn/beginner-html-site/gh-pages/images/firefox-icon.png" alt="Firefox icon" />
```

- **Attribute:**
<img src="https://github.com/user-attachments/assets/18e49d25-ffd1-416b-9ea6-e8ba3019e708" alt="image" width = 600/>


- **Whitespace**
  
Both are the same
```html
<p id="noWhitespace">Dogs are silly.</p>

<p id="whitespace">Dogs
    are
        silly.</p>
```

- **Special characters**
<img width="668" height="288" alt="image" src="https://github.com/user-attachments/assets/d1e5921c-c915-4fe1-9fa1-9df30e87ba51" />

- **Comment**
```html 
<!-- abc -->
```

- **Turn a text to a link:**
```html
<a href = "link.com"> abc </a>

To add words before and after:
<p> i love <a href = "link.com"> abc </a> hehe.</p>

To open a link in a new tab seperately from your current one:
<p> See more <a href="link.com" target="_blank" rel="noopener noreferrer">cat photos</a> in our gallery.</p>

NOTES:
 + target=_blank : Opens in a new tab
 + target=_self :	Opens in the same tab
 + rel="noopener noreferrer" : new page can't access your page through
```

- **Turn an image to a link:**
```html
<a href = "link.com" target="_blank" rel="noopener noreferrer">
  <img src = "image.jpg" alt = "photo">
</a>
```

- **Add caption under an image"**
```html
<figure>
  <img src="image.jpg" alt="A description of the image">
  <figcaption>A cute cat</figcaption>
</figure>
```

- **Add an ordered or unordered list:**
```html
<ul>
  <li>catnip</li>
  <li>laser pointers</li>
  <li>lasagna</li>
</ul>

NOTES:
 + ol: ordered list : using number to list
 + ul: unordered list : using dot
```

-**Anatomy of an HTML document:**
```html
<html lang="en-US">
  <head>
    <meta charset="utf-8" />
    <title>My test page</title>
  </head>
  <body>
    <main>
      <h1>
      <section>
        <h2>This is the first section</h2>
        <p>This is my page</p>
      </section>
      <section>
        <h2>This is the second section</h2>
        <p>This is my page</p>
      </section>
    </main>
  </body>
</html>
```


