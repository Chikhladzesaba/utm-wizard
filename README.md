# UTM Wizard

**Build correct UTM links step by step, and understand them along the way.**

👉 **Try it:**  https://chikhladzesaba.github.io/utm-wizard/

---

## Why this exists

"Add UTMs to every link we share" is a common request in marketing teams. For someone new, it's confusing: what is a source, what is a medium, and why does `cpc` matter?

Small mistakes add up. `Facebook` and `facebook` show up as two different sources. Paid ads tagged as `social` get mixed with free posts. Unknown values end up as "Unassigned" in Google Analytics, where nobody can use them.

UTM Wizard is your guide. You don't need to know the rules: answer a few plain questions, and the wizard builds a correct link and explains why each part is there. After a few links, you understand how UTMs work.

## How it works

1. **Where should people land?** Paste the page you're promoting.
2. **Where will people click this link?** Pick a plain-language option like *Facebook ad*, *Instagram post* or *Newsletter*. The wizard fills in the correct source and medium for you.
3. **What are you promoting?** Write the campaign name any way you like. The wizard cleans it into a consistent, report-friendly format.
4. **Your link.** Copy it, and see each part explained in plain words.

## What makes it different

- **Teaches while you build.** Every step has a short "Learn" box, so new team members understand UTMs instead of just copying them.
- **Speaks human.** You choose "Facebook ad", not "utm_medium = cpc". The wizard knows the conventions.
- **GA4 channel preview.** Before you share a link, see which Google Analytics 4 channel it will land in (Paid Social, Email, Organic Social…), with a warning when it would end up as "Unassigned".
- **Automatic cleanup.** Lowercase, hyphens instead of spaces, no special characters.

## Channel cheat sheet

| You pick | source | medium | GA4 channel |
|---|---|---|---|
| Facebook ad | facebook | cpc | Paid Social |
| Facebook post | facebook | social | Organic Social |
| Instagram ad | instagram | cpc | Paid Social |
| Instagram post / story | instagram | social | Organic Social |
| LinkedIn post | linkedin | social | Organic Social |
| Newsletter / email | newsletter | email | Email |
| Google Ads | google | cpc | Paid Search |
| QR code on a poster | poster | qr | Unassigned |

The channel predictions are a simplified version of GA4's default channel rules.

## Built with

One HTML file with plain HTML, CSS and JavaScript, hosted on GitHub Pages. No frameworks, no server, no database. Everything runs in your browser, and nothing you type is stored or sent anywhere.
