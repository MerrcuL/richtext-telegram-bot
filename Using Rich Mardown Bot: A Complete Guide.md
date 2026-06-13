## 🚀 Two Ways to Use the Bot

### 1. In Private Chat (Direct Mode)
* Open the bot in Telegram.
* Click the **Open Editor** button (or the menu button).
* This launches the Web App Composer.
* Write your text using Markdown, see a real-time live preview of how it looks, and click **Share / Send** or copy the formatted text.

### 2. In Any Chat (Inline Mode)
You can compose and send formatted messages in *any* chat (group, channel, or private chat with others) without adding the bot there!
1. In the input box of any chat, type: `@richtextsbot` followed by a space.
2. A button saying **Send Rich Message** will pop up above your keyboard.
3. Tap it to open the composer.
4. Write and format your message.
5. Tap **Send to Chat** to instantly send the formatted message directly into the conversation.

---

## 📝 Markdown Syntax Cheat Sheet

RichText Bot supports full markdown with premium rendering. Here is how to format your text:

### Basic Styling
* **Bold:** Wrap text in double asterisks: `**text**`
* *Italic:* Wrap text in single asterisks: `*text*`
* ~~Strikethrough:~~ Wrap text in double tildes: `~~text~~`
* `Inline Code`: Wrap text in single backticks: `` `code` ``
* ||Spoiler (Hidden Text)||: Wrap text in double vertical bars: `||spoiler||`

### Headings
Create section headings by prefixing the line with `#` symbols followed by a space:
```markdown
# Header 1 (Large)
## Header 2 (Medium)
### Header 3 (Small)
```

### Lists & Checklists
* **Unordered List:** Start lines with `-` or `*`
* **Ordered List:** Start lines with `1.`, `2.`, etc.
* **Interactive Checklists:** Start lines with `- [ ]` for unchecked tasks, or `- [x]` for checked tasks.
  * *Example:*
    * `- [ ] Task 1`
    * `- [x] Completed Task`

### Blockquotes & Collapsible Details
* **Quote:** Start lines with `>` to create a blockquote block.
* **Collapsible Details (Spoilers):** Use HTML `<details>` tags:
  ```html
  <details>
    <summary>Click to reveal more</summary>
    This content is hidden inside a collapsible block!
  </details>
  ```

### Tables
Create structured tables using standard Markdown table syntax:
```markdown
| Feature | Supported | Notes |
| :--- | :---: | :--- |
| Headers | Yes | Clean Obsidian-like style |
| Spoilers | Yes | Blur-to-reveal |
| Tables | Yes | Auto-aligned |
```

---

## 🌟 Advanced Layouts

### Slide / Card Layouts
Create beautiful horizontal layout sections by grouping content with separators (`---` or `***`) to structure your message visually.

