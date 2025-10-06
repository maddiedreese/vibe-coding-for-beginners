# Vibe Coding for Beginners

I like making things — small web apps, prototypes, or whatever idea comes to mind that week.  
This guide is a breakdown of how I work with AI tools, what I use, and how beginners can start doing the same.

---

## Table of Contents
- [How I Start a Project](#how-i-start-a-project)
- [Recommended Tools for Beginners](#recommended-tools-for-beginners)
  - [Lovable.dev](#lovabledev)
  - [Bolt.new](#boltnew)
  - [Anything](#anything)
- [Debugging and Problem Solving](#debugging-and-problem-solving)
- [Security Basics](#security-basics)
- [Integrations and Backends](#integrations-and-backends)
- [Backing Up Your Projects](#backing-up-your-projects)
- [Design and Styling](#design-and-styling)
- [Open Graph Tags](#open-graph-tags)
- [Custom Domains and Hosting](#custom-domains-and-hosting)
- [Final Thoughts](#final-thoughts)

---

## How I Start a Project

When I get an idea, I start by dumping everything into ChatGPT — all the scattered thoughts, features, and random notes that are in my head.

Then I ask it to guide me with questions like:
- Should this be a web app or mobile app?
- What features would make sense?
- What might the user flow look like?
- How can I make this work technically?

After going back and forth, I end up with:
- A clear outline  
- A list of features  
- A short description I can use inside my builder

Once I have that, I move into my tool of choice.

---

## Recommended Tools for Beginners

If you’re new to vibe coding, start with one of these.

### [Lovable.dev](https://lovable.dev)

Lovable is the easiest starting point. It’s designed for building fast while still producing real, working web apps.  
You can use AI to scaffold your app, connect a backend, or integrate an API — without getting lost in setup.

### [Bolt.new](https://bolt.new)

Bolt is great for semi-technical projects. You’ll probably open a terminal at least once, but the visual interface keeps you from getting bogged down.  
I use it for websites and apps that need a little backend logic but don’t require a full-stack setup.

### [Anything](https://www.createanything.com/?via=maddie)

This is my go-to for mobile apps built right in the browser.  
It’s flexible and visual, which makes it a good fit for quick iterations and testing ideas.

---

## Debugging and Problem Solving

Even with AI tools, you’ll run into errors. When that happens, take an active role in debugging — don’t just rely on the assistant to fix it for you.

Here’s what I do:
1. Check the logs — console logs, edge function logs, or error messages.  
2. Ask questions inside the tool’s built-in chat or discussion feature.  
3. Read the documentation for any API or integration I’m using.  
4. If I’m still stuck, I copy the error logs into ChatGPT and have a back-and-forth conversation to understand the problem.

The goal isn’t just to get it working — it’s to understand what broke and why.

---

## Security Basics

If your app has users, enable **Row Level Security (RLS)**.  
It’s a simple but important step that prevents users from seeing data that isn’t theirs.

Most of these tools — Lovable, Bolt, and Anything — use **[Supabase](https://supabase.com/)** behind the scenes, and it supports RLS by default.  
Just ask your coding tool to help you enable it.

---

## Integrations and Backends

Lovable, Bolt, and Anything make it simple to add both AI features and real backends.  
Some use Supabase under the hood, which gives you a working database and authentication without extra setup.

If you want to dig deeper, you can integrate directly with Supabase to see how your data and tables are structured.

---

## Backing Up Your Projects

Always sync your projects to **[GitHub](https://github.com/)**.  
All three platforms let you connect your GitHub account and automatically back up your code.

It’s the easiest way to keep your work safe, track versions, and prepare for deployment later.

---

## Design and Styling

Even if you’re not a designer, take a little time to adjust how your project looks. Small details go a long way.
- Change your font — [Google Fonts](https://fonts.google.com/) has plenty of free, high-quality options.  
- Experiment with colors using [Coolors.co](https://coolors.co/) to build or test palettes.  
- Browse [Dribbble](https://dribbble.com/) or [Mobbin](https://mobbin.com/) to get a sense of current design patterns.

I usually tweak nearly every visual element of my projects.  
If I’m not sure how to describe something, I’ll take a screenshot, paste it into ChatGPT, and ask how to explain that design element in developer terms.  
It helps me communicate my ideas clearly.

---

## Open Graph Tags

Open Graph tags control how your site appears when it’s shared online — the title, image, and description that show up in link previews.  
Most tools let you customize these in the project settings.

Always change them so that your links display correctly and look intentional when shared or found in search results.

---

## Custom Domains and Hosting

You don’t have to use a custom domain, but you should change the default domain that the tool gives you to something that fits your project better.  
Sometimes the default doesn’t reflect what your project has become, and updating it helps with presentation and clarity.

If you want to self-host, here’s a simple path:
1. Sync your project to GitHub.  
2. Connect it to [Netlify](https://www.netlify.com/) (their free plan usually works fine).  
3. Deploy automatically from your main branch.  
4. If you decide to use a custom domain, you can buy one from any registrar (I use [GoDaddy](https://www.godaddy.com/)) and follow the tool’s setup guide.

All of these platforms provide specific instructions for linking your domain.

---

## Final Thoughts

Start small, stay curious, and take ownership of the process.  
The more you build, the faster you’ll start connecting the dots.
