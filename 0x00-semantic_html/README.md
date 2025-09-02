# 📄 Semantic HTML Practice

## 🎯 Objective  
The goal of these tasks was to progressively practice structuring HTML documents using semantic elements, enhance them with meta tags for SEO and accessibility, create a **blog post layout**, and finally improve **form accessibility using ARIA roles and attributes**.  

---

## 📝 How I Approached the Tasks  

### Task 1: Creating `0-index.html`  
- I began by creating a new file named **`0-index.html`**.  
- The first step was adding the **doctype declaration** `<!DOCTYPE html>` to define the document as HTML5.  
- Next, I added the root `<html>` tag, and inside it, I placed the `<head>` (kept empty for now) and the `<body>` tags.  
- Inside the `<body>`:  
  - I built a `<header>` element that contains a `<nav>` with three navigation links.  
  - I then created a `<main>` section to hold the primary content.  
    - Inside `<main>`, I added an `<article>` with:  
      - A `<h1>` for the article’s title.  
      - A `<section>` to hold the article’s content.  
  - At the bottom, I added a `<footer>` with the text: `@copyright`.  
- Finally, I reviewed the structure to make sure it followed **semantic HTML5 best practices** for readability, accessibility, and SEO.  

---

### Task 2: Enhancing `1-index.html`  
- I copied the content of **`0-index.html`** into a new file named **`1-index.html`**.  
- Inside the `<head>` section, I added meta tags to improve SEO, accessibility, and responsiveness:  
  - `<meta charset="utf-8">` to define the character encoding.  
  - `<meta name="description">` to summarize the content of the page.  
  - `<meta name="keywords">` to provide relevant keywords.  
  - `<meta name="author">` to specify the author of the page.  
  - `<meta name="viewport">` to ensure the page scales well on mobile devices.  
- I also added a `<title>` tag with the text **"Semantic Html Blog Post"** so that the document has a descriptive title.  
- These changes improved the document’s **search engine visibility**, **mobile responsiveness**, and **overall accessibility**.  

---

### Task 3: Creating a Blog Layout in `2-index.html`  
- I copied the content of **`1-index.html`** into a new file named **`2-index.html`**.  
- Inside the `<header>`:  
  - I added an `<h1>` with the text **"My Blog"**.  
  - I created a `<nav>` containing a `<ul>` with three `<li>` elements linking to **Home**, **About**, and **Contact**.  
- Inside the `<article>` (within `<main>`):  
  - I added a `<header>` containing an `<h2>` titled **"Understanding Semantic HTML"**.  
  - I included a `<p>` with a **published date**, using a `<time>` element for proper semantics.  
  - For the main content, I structured it with **three `<section>` blocks**:  
    1. **Introduction Section**:  
       - `<h3>` with the text **"Introduction"**.  
       - `<p>` explaining how semantic HTML improves accessibility and SEO.  
    2. **Main Content Section**:  
       - `<h3>` with the text **"Main Content"**.  
       - `<p>` describing the importance of `<article>`, `<section>`, and `<header>` tags.  
       - `<figure>` with an `<img>` (with `alt="example"`) and `<figcaption>` describing the illustration.  
    3. **Conclusion Section**:  
       - `<h3>` with the text **"Conclusion"**.  
       - `<p>` emphasizing how semantic HTML improves accessibility, SEO, and navigation.  
  - Finally, I added a `<footer>` inside the `<article>` with:  
    - A `<p>` stating **"Written by <name>"**.  
    - A `<p>` stating **"Published on 2024-09-11"**.  
- This created a complete **blog-style layout** using semantic HTML, ensuring clarity, accessibility, and strong document structure.  

---

### Task 4: Adding and Enhancing Form Accessibility in `3-index.html`  
- I copied the content of **`2-index.html`** into a new file named **`3-index.html`**.  
- Inside the `<main>` element, I added a new `<section>` containing a **form** with ARIA attributes for accessibility:  
  - `<form action="#" method="POST" aria-labelledby="form-title" role="form">`.  
- Inside the form:  
  1. A **Name field** inside a `<div>`:  
     - `<label for="name">Name</label>`  
     - `<input type="text" id="name" name="name" aria-required="true">`.  
  2. An **Email field** inside another `<div>`:  
     - `<label for="email">Email</label>`  
     - `<input type="text" id="email" name="email" aria-required="true">`.  
  3. A **Submit button** inside another `<div>`:  
     - `<button type="submit" aria-label="Submit the form">Submit</button>`.  
  4. A `<div aria-live="polite" role="alert"></div>` to provide accessible feedback messages.  
- These changes ensure that **screen readers** and assistive technologies can properly interpret the form, improving **usability and accessibility** for all users.  

---
