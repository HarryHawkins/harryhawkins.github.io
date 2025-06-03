---
layout: post
title: How I Used Generative AI to Migrate My Website (and Why I’d Do It Again)
---

Recently, I migrated my personal website from a dated custom setup to a more modern static site generator, specifically **[Jekyll](https://jekyllrb.com/)** using the **[Chirpy theme](https://github.com/cotes2020/jekyll-theme-chirpy)**. The last time I built the site, in 2021, it took days of trial and error, reading outdated documentation, and digging through theme code just to get something functional. This time, I used ChatGPT to help, and I probably completed the same scope of work in 10% of the time. Hours, not days. 

That speed-up didn’t come from the AI doing everything for me. It came from not getting stuck, not wasting time, and not having to remember every detail of Liquid templating or the quirks of Jekyll. Here’s what the process looked like, and what I learned from using AI as my co-pilot.

---

### The Problem

My old site worked, but it was clunky. It used the same premise, GitHub Pages and Jekyll, but it was dated and ugly, the folder structure was inconsistent, the layout was patched together, and it lacked the fancy design features that modern themes offer out of the box (check out the dark mode toggle on this!). I wanted something faster and more maintainable, but the idea of rewriting everything such as the layout logic, file structure etc sounded exhausting.

Back in 2021, I powered through that kind of work manually and it was fun and I learnt a lot. This time, I outsourced the friction to AI. I do think that if I hadn't done it myself before, even with AI's help this would have been slower/fiddly.

---

### What I Used AI For

Here are some of the key areas where generative AI sped things up massively:

* **Explaining modern Jekyll architecture**: Instead of reading scattered docs or GitHub threads, I could just ask "What is `_includes` used for in Chirpy?" and get a clear answer. This alone saved hours.
* **Converting content formats**: I pasted in samples of my old markdown posts, and the AI rewrote them to match Chirpy's front matter, formatting, and folder structure instantly.
* **Fixing obscure errors**: When Jekyll failed with an error like `include head.html not found`, I didn’t have to guess. The AI walked me through which file was missing, where to find it, and how the layout inheritance worked.
* **Customising the theme**: I wanted to make the site feel more “me” without breaking the theme. I described the changes I had in mind, and the AI guided me to the exact files and snippets to edit.

In short, it made me *10x faster*. But here’s the thing, I still needed to know what I was doing.

---

### You Still Need Technical Literacy

AI is great at generating code, explaining things, and even debugging. But you need enough foundational knowledge to:

* Know what to ask
* Interpret its answers
* Judge whether the solution makes sense
* Understand how changes affect the whole system

If I didn’t already have a computer science background or a decent understanding of how static sites work, this would have been very hard. It would be like being handed ingredients and instructions without knowing how to cook — possible, but easy to mess up.

So yes, AI helped a lot. But it amplified my skills rather than replacing them.

---

### What I Still Had to Do Myself

The AI didn’t do everything:

* I ran the site locally, checked styles, and inspected what was rendering
* I chose how to structure the site and how I wanted it to feel
* I sanity-checked AI’s suggestions, especially when it gave me old or incorrect file paths
* I made the creative decisions, like what content to include and how to present it

The migration was smooth, but it still took hands-on work and attention to detail. AI helped me navigate faster, but I was still driving.

---

### Why I’d Do It Again

The best part of using generative AI wasn’t that it wrote code for me. It was that it removed the *friction*. I never felt stuck. I didn’t spend 30 minutes debugging a missing colon or trying to trace a layout inheritance chain manually. I got unstuck in seconds and I could move on.

And unlike tutorials or Stack Overflow threads, the AI tailored its responses to *my* project, *my* folder structure, and *my* goals. That personalisation is what made the experience so productive.

---

### Final Thoughts

This was a clear case where AI made me dramatically more productive. But it worked because I knew what I was doing. If you don’t have some base level of coding literacy, the output might look like magic but feel unusable.

If you're a developer, even a casual one, treat it like a very fast, always-available collaborator. You’ll still own the work, but you'll spend less time stuck in the weeds and more time actually building something.

**Note:** If you want to see what the old site looked like, check it out on the Wayback Machine. It’s a really cool tool that lets you browse past versions of websites, like a time machine for the internet.

---
