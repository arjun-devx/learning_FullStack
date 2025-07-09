# Raw Problem

Create a **Projects** section where projects will be showcased using proper HTML structure including headings, divs, and images with project logos and descriptions.

---

## ✅ Requirements

Use the following HTML tags in a proper semantic and structured flow:

1. Use a `<section>` tag to contain all content for the Projects section.
2. Use an `<h1>` tag with the text: **"My Projects"** for the section heading.
3. Use a `<div>` tag to group all elements associated with a **single project**.

### For Each Project (inside the `<div>`):
- ✅ Use an `<img>` tag for the project’s logo or image.
- ✅ Use an `<h2>` tag for the project’s **name/title**.
- ✅ Use a `<p>` tag for the project’s **description**.

---

## ⚠️ Notes

- Do not use real links or actual image URLs if not required. Use placeholder values (e.g. `src="#"`).
- Refer to the provided test cases (if any) to validate the structure and content.
- Ensure each project is wrapped cleanly in its own `<div>`.

---

## 📌 Example HTML Structure

```html
<section>
  <h1>My Projects</h1>

  <div>
    <img src="#" alt="Project 1 Logo">
    <h2>Project One</h2>
    <p>This is a description of Project One.</p>
  </div>

  <div>
    <img src="#" alt="Project 2 Logo">
    <h2>Project Two</h2>
    <p>This is a description of Project Two.</p>
  </div>
</section>
