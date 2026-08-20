# blog-to-email — a free Claude skill by Benchmark Email

Turn any blog post into a high-performing "one idea" marketing email — the exact AI pipeline behind [Benchmark Email](https://www.benchmarkemail.com)'s *Marketing Minute*, the sends that opened at more than double the rate of our traditional digest newsletter.

**What it does:** paste a blog URL and Claude runs our pipeline — an insight memo grounded in the source (no invented claims), a one-idea email draft that never reuses the blog title, subject line options, and a social teaser. You review and hit send. The AI never touches the button.

Full story with the numbers: [[We Gave our Newsletter to AI Agents]](https://x.com/JessicaLunk/status/2090521152154157471)

## Install

**Claude app (web or desktop):** download [`SKILL.md`](https://raw.githubusercontent.com/Benchmark-Email/blog-to-email-skill/main/SKILL.md), attach it to any Claude chat, and save it as a skill when Claude offers.

**Claude Code:**

```
mkdir -p ~/.claude/skills/blog-to-email
curl -o ~/.claude/skills/blog-to-email/SKILL.md https://raw.githubusercontent.com/Benchmark-Email/blog-to-email-skill/main/SKILL.md
```

## Use

Just ask: *"Turn this post into an email: https://yourblog.com/your-post"*

**Pro tip from our own pipeline:** post 3–4 repurposed editions on LinkedIn first, one per week, and email only the best performer. Your list should never get a guess.

## No email platform yet?

[Create a free Benchmark Email account](https://www.benchmarkemail.com) — up to 500 contacts and 2,500 sends a month, full features on every plan.

## License

MIT — free to use, share, and adapt. Built by [Benchmark Email](https://www.benchmarkemail.com).
