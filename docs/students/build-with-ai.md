---
hero_image: assets/images/heroes/hero-build-ai.svg
hero_alt: Green and pink banner for the Build with AI workshop
hero_title: Build with AI
hero_subtitle: Workshop 4 of 4 — Students Track
---

# Build with AI

<span class="ws-badge ws-badge--students">Students Track · Workshop 4 of 4</span>

**Duration:** 60–90 minutes  
**Prerequisites:** [Workshop 2: GitHub Basics](github-basics.md) is recommended

---

## What You'll Learn

- [x] Use AI tools to help build a real project
- [x] Create a simple website using GitHub Pages
- [x] Use AI to generate content and ideas
- [x] Understand how AI assists developers
- [x] Publish something on the internet — for free!

---

## You're Ready to Build 🔨

You've learned what AI is, you have a GitHub account, and you understand how products are created. Now let's put it all together and make something real.

By the end of this workshop, you will have **a live website on the internet** that you built using GitHub and AI tools.

---

## Part 1 — What Is GitHub Pages?

**GitHub Pages** is a free feature of GitHub that lets you publish a website directly from your repository.

How it works:
1. You create files in a GitHub repository
2. GitHub Pages automatically turns those files into a live website
3. Your website gets a free URL like: `https://yourusername.github.io/your-repo-name`

This is exactly how this Workshop Hub website was built!

---

## Part 2 — Plan Your Website With AI

Before building, we'll use an AI tool to help us plan. Let's use ChatGPT.

### Step 1: Open ChatGPT

Go to [chat.openai.com](https://chat.openai.com) and sign in.

### Step 2: Describe Your Idea

Type a prompt like this (customise it for your own website idea):

> *"I want to create a simple personal website. I'm a Year 12 student interested in music and environmental science. Can you suggest 4-5 sections I should include and write a short paragraph for each one?"*

### Step 3: Review and Edit

Read what ChatGPT gives you. Ask yourself:
- Does this sound like me?
- Is anything incorrect or not relevant?
- What would I change?

Edit the content so it's genuinely yours. **AI gives you a starting point — you make it real.**

!!! note "Always personalise AI-generated content"

    Content that comes straight from AI often sounds generic. The best results come when you take AI's suggestions and rewrite them in your own voice.

---

## Part 3 — Create Your Website Files

Now let's build it on GitHub.

### Step 1: Create a New Repository

1. Go to GitHub and create a new repository
2. Name it: `yourusername.github.io` — **this is the special name that activates GitHub Pages for your main profile site**

   For example, if your username is `aisha-learns`, your repo should be: `aisha-learns.github.io`

3. Make sure it's set to **Public**
4. ✅ Add a README file
5. Click **Create repository**

### Step 2: Create Your Homepage

1. In your new repository, click **"Add file"** → **"Create new file"**
2. Name it: `index.html`
3. Paste this starter code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Website</title>
  <style>
    body {
      font-family: 'Segoe UI', Arial, sans-serif;
      max-width: 800px;
      margin: 0 auto;
      padding: 2rem;
      background: #f0f9ff;
      color: #1e293b;
    }
    h1 { color: #0ea5e9; }
    h2 { color: #0284c7; border-bottom: 2px solid #b8e6fb; padding-bottom: 0.3rem; }
    .card {
      background: white;
      border-radius: 1rem;
      padding: 1.5rem;
      margin: 1rem 0;
      box-shadow: 0 2px 8px rgba(14,165,233,0.1);
    }
    a { color: #ec4899; }
  </style>
</head>
<body>
  <h1>👋 Hi, I'm [Your Name]</h1>
  <p>Welcome to my website! I built this using GitHub Pages and AI tools.</p>

  <div class="card">
    <h2>About Me</h2>
    <p>Write something about yourself here. Use the content ChatGPT helped you create — but make it sound like you!</p>
  </div>

  <div class="card">
    <h2>What I'm Learning</h2>
    <p>Describe what you're studying or exploring right now.</p>
  </div>

  <div class="card">
    <h2>My Interests</h2>
    <p>What do you love to do? What are you curious about?</p>
  </div>

  <div class="card">
    <h2>My Goals</h2>
    <p>What do you want to achieve? What are you working towards?</p>
  </div>

  <footer style="margin-top:3rem; color:#94a3b8; font-size:0.9rem;">
    Built with GitHub Pages · Workshop Hub Student
  </footer>
</body>
</html>
```

4. Replace `[Your Name]` and the placeholder content with your own content from the ChatGPT exercise
5. Commit the file

### Step 3: Enable GitHub Pages

1. Go to your repository **Settings** (the tab on the right)
2. In the left sidebar, click **Pages**
3. Under "Source", select **"Deploy from a branch"**
4. Select the **"main"** branch and **"/ (root)"** folder
5. Click **Save**

GitHub will now build your website. This takes 1–2 minutes.

---

## Part 4 — View Your Live Website!

After a couple of minutes:

1. Refresh the GitHub Pages settings page
2. You'll see a message: *"Your site is live at https://yourusername.github.io"*
3. Click the link — **your website is live on the internet!** 🎉

!!! tip "It might take a few minutes"

    If it's not working immediately, wait 2–3 minutes and refresh the page. GitHub needs time to deploy your site.

---

## Part 5 — Use AI to Improve Your Site

Now that you have a working site, let's use AI to enhance it.

### Ask ChatGPT for Help

Try these prompts:

**For content:**
> *"Can you write a short, friendly 'About Me' section for a website? I'm 17, I love environmental science and want to work in renewable energy one day."*

**For design ideas:**
> *"What are some simple CSS changes I could make to a website to make it look more colourful and modern? I want a light blue and pink theme."*

**For a new section:**
> *"Can you write some HTML for a 'Projects' section that lists 3 things I've worked on? Use cards with a title and description."*

Copy the suggestions, review them, and add them to your `index.html` file — then commit and your site updates automatically!

---

## Part 6 — How AI Helps Developers

You've just experienced something that professional developers do every day. AI coding tools like **GitHub Copilot** suggest code as you type, answer questions, and help debug problems.

This doesn't mean developers have nothing to do — it means they can:
- Move faster
- Try more ideas
- Focus on problem-solving instead of remembering syntax
- Learn from AI suggestions

!!! note "AI is a collaborator, not a replacement"

    The best developers use AI as a powerful assistant. They still make the important decisions about what to build and why. Understanding how to work with AI is one of the most valuable skills you can develop right now.

---

## Key Takeaways

- You built and published a real website using GitHub Pages — for free!
- AI tools helped you plan and create content quickly
- GitHub Copilot and similar tools help developers write code faster
- The key skills: knowing what to ask, evaluating the output, and making it your own
- You've now completed the Students Track — celebrate that! 🎊

---

## What's Next?

You've finished the Students Track. Here are some ideas for what to do next:

- **Keep building**: Add more pages to your website, improve the design
- **Learn HTML and CSS**: Try [freeCodeCamp](https://freecodecamp.org) for free interactive lessons
- **Explore GitHub further**: Look at open-source projects, contribute to something
- **Try the Leaders Track**: Understand how the technology you're learning fits into business and organisations
- **Check the Resources page**: We've collected the best free learning materials

---

[← Workshop 3: Product Development](product-development.md)  
[Explore Resources →](../resources.md){ .md-button .md-button--primary }
