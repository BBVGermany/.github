## Hi there 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

Use:
```
gh repo list BBVGermany --limit 4000 | while read -r repo _; do   gh repo clone "$repo" "$repo"; done
```

to clone all repos in this orga. Default limit would be 30.

to use this you need the gh client with a verificated acc.
