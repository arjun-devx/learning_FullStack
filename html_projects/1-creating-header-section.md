# Raw Problem

**Raw Problem**  
Create a simple Nav bar and Header section using plain HTML only.

## ✅ Requirements

### Nav Bar
- Use `<a>` tags to add the redirectable links.

### Header Section
- Use an `<img>` tag to add a person's image.
- Use heading tags (`<h1>`, `<h2>`, etc.) to add the person's name and summary/title.
- Use a `<button>` tag to add a button for downloading the resume.

> ⚠️ **WARNING**:  
> - Do not use actual URLs for `href` or `src` attributes.  
> - Use `#` as a mock link.  
> - For the image, use `'profile-img.jpg'` as the `src`.

## 📌 Notes

Refer to the test cases to understand the required structure and validations to pass the submission.

---

### Basic Expected HTML Structure (for reference)

```html
<header>
  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Projects</a>
    <a href="#">Blog</a>
  </nav>
</header>

<div>
  <img src="profile-img.jpg" alt="profile image">
  <h1>{PERSON_NAME}</h1>
  <h2>I'm a Frontend<br>Developer</h2>
  <button>DOWNLOAD RESUME</button>
</div>
