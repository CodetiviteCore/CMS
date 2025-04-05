## ✨ What This Tool Does

This tool lets you write simple notes using symbols like `#`, `*`, and `[]()` and turns them into beautiful, styled content like what you see on websites or blogs.

It’s like magic for text! 🪄  
You type normally, add a few symbols — and boom 💥 — styled text, titles, images, and links show up beautifully.

---

> Note: Use [readme.so](readme.so) to preview your text

## ✍️ How to Use It (No Tech Needed)

Here’s how to write different things using **easy symbols**:

---

### 🧠 Titles / Headings

Make big bold titles by starting a line with:

| What You Type            | What You See                    |
|--------------------------|----------------------------------|
| `# Big Title`            | <h1>Big Title</h1>               |
| `## Medium Title`        | <h2>Medium Title</h2>            |
| `### Small Title`        | <h3>Small Title</h3>             |

---

### 💬 Quotes

Add a quote from someone:

```
> This is a quote
```

➡️ This becomes a nice gray block for quotes.

---

### 🔤 Text Styling

Use these symbols to style your text:

| Style              | How To Write It      | Looks Like       |
|--------------------|----------------------|------------------|
| **Bold**           | `**bold text**`      | **bold text**    |
| *Italic*           | `*italic text*`      | *italic text*    |
| _Underline_        | `_underlined text_`  | <u>underlined text</u> |
| ~~Strikethrough~~  | `~~old~~`            | ~~old~~          |
| ***Bold + Italic***| `***wow***`          | ***wow***        |

---

### 📦 Code (Special Formatting for Tech Text)

To show code or commands, wrap it in backticks:

#### 1️⃣ Inline code:
```
Here’s some `inline code`
```

#### 2️⃣ Big code block:
Use 3 backticks (```) before and after the code:

<pre>
```bash
npm install
```
</pre>

<pre>
```javascript
function sayHi() {
  console.log("Hi!")
}
```
</pre>

---

### 📋 Lists (Bullets & Steps)

#### Bullet list:
```
- Item 1
- Item 2
```

➡️ Shows as:
- Item 1  
- Item 2

#### Numbered list:
```
1. Step One
2. Step Two
```

➡️ Shows as:
1. Step One  
2. Step Two

---

### 🖼️ Images

To show an image:

```
![Description](image-link.jpg)
```

You can even size the image like this:

```
![Cat Picture](cat.jpg "300,200")
```

🖼️ It’ll display the image at 300×200 pixels.

---

### 🔗 Links (With Tracking!)

Want to make something clickable?

```
[Click Here](https://example.com)
```

➡️ Becomes a link that opens in a new tab, and your system will also track that the link was clicked ✅

---

### 📄 Paragraphs

Just press **Enter twice** to start a new paragraph.

Like this:

```
This is paragraph one.

This is paragraph two.
```

---

### 🔥 Extra Features

- `---` creates a horizontal line to separate sections.
- The parser also supports common developer docs like `.env`, `npm install`, `git clone`, etc.

---

## 🎯 Who Is This For?

Anyone writing newsletters, project documentation, onboarding guides, blog posts, or instructions — even if you’re not technical!

If you can write in plain English, this tool makes it look great for the web.

---

## 👩🏽‍💻 Bonus (For Developers)

This parser:

- Converts Markdown to HTML
- Supports advanced styling like images with dimensions, link tracking, and fenced code blocks
- Outputs clean HTML you can inject via `innerHTML` in frontend frameworks