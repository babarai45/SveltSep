<div align="center">
  <h1 style="color:#ff6600;font-size:56px;margin:0">🍊 Svelte Deep-Dive — Course & Docs</h1>
  <p style="font-size:18px;margin-top:8px;color:#444">Structured lessons • labs • examples • progress tracking</p>
</div>

<hr/>

<!-- Quick badges -->
<p align="center">
  <img src="https://img.shields.io/badge/course-ready-green" alt="status"/>
  <img src="https://img.shields.io/badge/level-intermediate-blue" alt="level"/>
  <img src="https://img.shields.io/badge/format-md%2Bhtml-orange" alt="format"/>
</p>

---

## 📚 Course Outline (high level)
1. Introduction to Svelte & philosophy  
2. Getting Started: Tooling & SvelteKit  
3. Core Concepts: components, reactivity, props, slots  
4. State Management: stores, context, patterns  
5. Styling & design systems  
6. Advanced: SSR, routing, code-splitting, animations  
7. Testing, CI & deployment  
8. Example projects & labs

---

## 🌟 Today's Lesson — Day 01: Internet (example)
<div style="display:flex;gap:20px;flex-wrap:wrap;justify-content:center">

<!-- card -->
<div style="border-radius:12px;padding:14px;max-width:820px;border:1px solid #fb6900ff;">
  <h2 style="margin-top:4px;color:#00a8ff">🌐 Day 01 — Internet</h2>

  <table style="width:100%;border-collapse:collapse;">
    <thead>
      <tr style="background:#fafafa">
        <th style="padding:8px;text-align:left">📘 Subtopic</th>
        <th style="padding:8px;text-align:left">🧠 Comcepts</th>
        <th style="padding:8px;text-align:left">🧪 Projects</th>
        <th style="padding:8px;text-align:left">📚 Resources</th>
        <th style="padding:8px;text-align:left">🔖 Status</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="padding:8px">Introduction</td>
        <td style="padding:8px"><a href="./Concepts/day01_sub1.md"><button type="bu">Read</button></a></td>
        <td style="padding:8px"><a href="./Labs/day01_lab1.md">Try</a></td>
        <td style="padding:8px"><a href="https://www.geeksforgeeks.org/computer-network-tutorials/">Link</a></td>
        <td style="padding:8px">✅ Done</td>
      </tr>
      <tr>
        <td style="padding:8px">History of Network</td>
        <td style="padding:8px"><a href="./Concepts/day01_sub2.md">Read</a></td>
        <td style="padding:8px"><a href="./Labs/day01_lab2.md">Try</a></td>
        <td style="padding:8px"><a href="https://internet-history.fandom.com/wiki/Internet_History">Link</a></td>
        <td style="padding:8px">🚧 In Progress</td>
      </tr>
      <tr>
        <td style="padding:8px">What is the Internet?</td>
        <td style="padding:8px"><a href="./Concepts/day01_sub3.md">Read</a></td>
        <td style="padding:8px"><a href="./Labs/day01_lab3.md">Try</a></td>
        <td style="padding:8px"><a href="https://www.cloudflare.com/learning/network-layer/what-is-the-internet/">Link</a></td>
        <td style="padding:8px">⏳ Pending</td>
      </tr>
    </tbody>
  </table>

  <p style="color:#666;margin-top:8px"><i>Tip:</i> <b>After Learing Each Concepts please Do Practics for for Strong Concepts </b>.</p>
</div>

</div>

---

## 🛠️ Lesson template (use for each `dayXX-*.md`)
Create a new file `docs/dayXX-topic.md` copy the template below.

```markdown
# Day XX — <Topic title>

## Objectives
- Objective 1
- Objective 2
- Objective 3

## ⏱ Estimated time
45–90 minutes

---

## 🧠 Theory
(Concise explanation, diagrams, code snippets)

### Key concepts
- concept A
- concept B

---

## 🧪 Lab / Hands-on
Step-by-step instructions.

```bash
# commands to run
npm create svelte@latest my-app
cd my-app
npm install
npm run dev


```
<!-- next -->


Example Svelte component:

```js

<script>
  export let name = "world";
</script>

<h1>Hello {name}!</h1>

```

🔁 Challenge (mini-project)

Build X in 60 minutes. Deliverables:

working repo link

short README with screenshots

📚 Further resources

Official docs: https://svelte.dev
