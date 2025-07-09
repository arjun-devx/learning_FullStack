# Raw Problem

Create an **About Me** section that includes the person's image, headings, an introduction, a description, and social profile links.

---

## ✅ Requirements

Use the following HTML tags in the proper semantic structure and flow:

1. Use a `<section>` tag to contain the entire **About Me** section.
2. Use an `<img>` tag to show the person's image.  
   - Include both `src` and `alt` attributes.
3. Use an `<h1>` tag for the section heading (e.g., "About Me").
4. Use an `<h3>` tag for the person's brief introduction (e.g., "Hi, I'm Arjun Sharma").
5. Use a `<p>` tag for a longer personal description or summary.
6. Add multiple `<a>` tags for social profile links.  
   - Each `<a>` must contain an `<img>` tag representing the social platform's logo.
   - These logos act as clickable redirects (use mock links like `href="#"`).

---

## ⚠️ Notes

- Use `"#"` for `href` attributes and `"#"` or placeholder filenames like `logo1.png` for image sources if no real URLs are provided.
- Each `<a>` tag should **only wrap the corresponding social logo `<img>`** — do not include text inside.
- Follow test case specifications for validations.

---

## 📌 Example HTML Structure

```html
<section>
  <img src="profile.png" alt="Profile Image">

  <h1>About Me</h1>
  <h3>Hi, I'm Arjun Sharma</h3>

  <p>
    I'm a frontend developer passionate about building user-friendly web experiences.
    I love working with HTML, CSS, and JavaScript to bring ideas to life.
  </p>

  <a href="#"><img src="logo1.png" alt="LinkedIn"></a>
  <a href="#"><img src="logo2.png" alt="GitHub"></a>
  <a href="#"><img src="logo3.png" alt="Twitter"></a>
</section>
