# 📘 Site Class Reference – Literal Naming Cheat Sheet

This file documents the literal class naming conventions used in your HTML/CSS system. No semantic HTML tags (like `<p>` or `<h1>`) are used — everything is styled via clear, descriptive class names.

---

## 🧱 Layout Structure

| Class Name     | Description                                         |
|----------------|-----------------------------------------------------|
| `header`       | Site header block (contains title and nav)         |
| `nav-bar`      | Horizontal navigation link container               |
| `main`         | The primary content block of the page              |
| `section`      | A major content section (About, Projects, etc.)    |
| `footer`       | Footer area with copyright or contact info         |

---

## 🧾 Typography

| Class Name          | Description                                      |
|---------------------|--------------------------------------------------|
| `heading-primary`   | Large title (e.g. site owner’s name)             |
| `heading-secondary` | Section titles (e.g. “Projects”, “Contact”)      |
| `paragraph`         | A full paragraph of readable text                |
| `bold-label`        | Text span meant to appear bold or emphasized     |

---

## 📋 Lists

| Class Name        | Description                                  |
|-------------------|----------------------------------------------|
| `project-list`    | Bullet-point list of projects or items       |

---

## 🎨 Fonts and Theming (from theme CSS)

| Class Name            | Description                               |
|------------------------|-------------------------------------------|
| `title-font`          | Uses “Fleur De Leah” cursive typeface     |
| `cutive-mono-regular` | Uses “Cutive Mono” monospace typeface     |
| `text-font`           | Optional monospace styling fallback       |

---

## 🛑 Anti-BS Policy

- No `<p>`, `<h1>`, or `<h2>` tags used.
- All elements are `<div>` or `<span>` with explicitly named classes.
- If you forget what something is, it’s in this file.