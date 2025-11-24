# 🌟 Comet Prompt Library

<div align="center">

![Hero Image](mockup-1763975546892.png)

**A curated collection of 40+ powerful Comet (Perplexity browser agent) prompts**  
to automate your daily workflows, boost productivity, and make repetitive tasks fun!

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Contributions](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Prompts](https://img.shields.io/badge/prompts-40+-orange.svg)](#prompt-categories)

</div>

---

## 🚀 What is Comet?

Comet is Perplexity's AI browser agent that can take control of your web browser to perform complex tasks. This library contains ready-to-use prompts that help you leverage Comet's capabilities for various real-world scenarios.

## 📋 Quick Start

1. **Browse Prompts** - Explore the categories below
2. **Customize** - Replace `{{PLACEHOLDER}}` values (e.g., `{{LANG}}`, `{{FROM}}`, etc.)
3. **Execute** - Paste the `### PROMPT` block into Comet's sidebar and run

### Example Usage
```markdown
### PROMPT
take control of my browser

Assume you are a principal engineer reviewing code written in {{LANG}}.

1. Scroll through every changed file in the current pull-request view.
2. Leave inline review comments on security, performance, and missing tests.
3. Add a summary note with three blockers and two nice-to-haves.
4. Open the "Preview" — do **not** press "Submit review".
```

## 📚 Prompt Categories

### 💻 **Coding** (4 prompts)
Developer workflows and code automation
- `pr-code-review.md` - Automated PR code reviews
- `leetcode-ladder.md` - LeetCode problem solver
- `smart-commit-message.md` - Intelligent commit messages
- `codewars-kata-climber.md` - Codewars kata completion

### 🎮 **Gamified** (20 prompts)
Turn boring tasks into engaging challenges
- `github-green-square-bot.md` - Maintain contribution streak
- `stackoverflow-rep-sniper.md` - Boost Stack Overflow reputation
- `duolingo-streak-saver.md` - Never lose your language streak
- `chesscom-tactics-grind.md` - Chess puzzles automation
- And 16 more gamified workflows!

### 💼 **Job Hunt** (2 prompts)
Career advancement and application automation
- `auto-apply-form-fill.md` - Automated job applications
- `linkedin-lead-scrape.md` - LinkedIn lead generation

### ⚡ **Productivity** (4 prompts)
Daily productivity boosters
- `notion-daily-journal.md` - Automated journaling
- `flight-deal-compare.md` - Flight price comparison
- `grocery-price-tracker.md` - Track grocery prices
- `linkedin-post-scheduler.md` - Schedule LinkedIn posts

### 🔄 **Repetitive** (10 prompts)
Automate tedious, repetitive tasks
- `email-unsubscribe-blitz.md` - Bulk email unsubscriber
- `password-rotator.md` - Secure password rotation
- `subscription-fee-hike-alert.md` - Monitor subscription prices
- `photo-duplicate-cleaner.md` - Clean duplicate photos
- And 6 more time-saving automations!

### 🛠️ **Misc** (1 prompt)
Template for creating your own prompts
- `template.md` - Starter template for custom prompts

## 🏗️ Prompt Structure

Each prompt follows a standardized YAML frontmatter structure:

```yaml
---
title: "Descriptive Title"
category: "coding|job-hunt|gamified|productivity|repetitive|misc"
scope: "website.com or @current"
automation: "manual|semi-auto|full-auto"
output_format: "markdown|json|inline-actions"
difficulty: "⚡ easy|⚙️ medium|🔧 finicky"
tags: ["tag1", "tag2", "{{PLACEHOLDER}}"]
---
```

### Difficulty Levels
- **⚡ Easy** - Straightforward tasks, high success rate
- **⚙️ Medium** - Some complexity, moderate success rate  
- **🔧 Finicky** - Complex tasks, may require adjustments

## 🎯 Featured Prompts

### 🔥 Most Popular
1. **GitHub Green Square Bot** - Never break your contribution streak
2. **Email Unsubscribe Blitz** - Clean your inbox in minutes
3. **PR Code Review Assistant** - Professional code reviews automatically

### 💡 Most Creative
1. **Duolingo Streak Saver** - Gamified language learning
2. **Chess.com Tactics Grind** - Improve chess rating automatically
3. **Habitica XP Farmer** - Level up your productivity game

### ⏰ Biggest Time Savers
1. **Meeting Slot Collector** - Find perfect meeting times
2. **Expense Receipt Sorter** - Organize receipts automatically
3. **Weekend Chore Scheduler** - Plan your weekend efficiently

## 🤝 Contributing

We love contributions! Here's how to get started:

1. **Fork** this repository
2. **Create** a new prompt using the `template.md`
3. **Test** your prompt thoroughly with Comet
4. **Submit** a pull request with detailed description

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

### Contribution Guidelines
- Follow the YAML schema in `schema.yaml`
- Test prompts with real websites
- Include clear instructions and examples
- Use appropriate difficulty indicators
- Add relevant tags for discoverability

## 📊 Statistics

| Category | Prompts | Difficulty |
|----------|---------|------------|
| 💻 Coding | 4 | ⚙️ Medium |
| 🎮 Gamified | 20 | ⚡ Easy |
| 💼 Job Hunt | 2 | 🔧 Finicky |
| ⚡ Productivity | 4 | ⚙️ Medium |
| 🔄 Repetitive | 10 | ⚡ Easy |
| 🛠️ Misc | 1 | ⚙️ Medium |
| **Total** | **41** | **Mixed** |

## 🔧 Technical Details

### Compatibility
- **Browser**: Chrome, Firefox, Safari, Edge
- **Platform**: Perplexity Comet
- **Format**: Markdown with YAML frontmatter

### Best Practices
- Always test prompts in a safe environment first
- Replace placeholders with actual values before use
- Monitor automation progress, especially for complex tasks
- Keep prompts updated with website changes

## 🐛 Troubleshooting

**Common Issues:**
- **Website layout changed** → Update selectors in prompt
- **Comet can't find element** → Add wait conditions or adjust timing
- **Prompt stops midway** → Break into smaller steps

**Get Help:**
- Check existing issues in this repository
- Join our community discussions
- Refer to Comet documentation

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Perplexity** for creating the amazing Comet browser agent
- **Contributors** who help expand this prompt library
- **Community** for testing and feedback

---

<div align="center">

**🌟 Star this repository if you find these prompts useful!**

Made with ❤️ by the Panda and Rabbit

[⬆️ Back to Top](#-comet-prompt-library)

</div>
