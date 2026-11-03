# QA Portfolio - Ritesh Kumar

I am an early-career QA engineer based in Bihar, open to relocation. This repo shows how I find, write and prioritise bugs. I am still building it up, so it is small for now.

## About me
- Hardware and system validation at Tejas Networks (Sept 2024 to Jan 2025)
- Training in Tricentis Tosca (Foundation certified) and Selenium
- B.Tech in Electrical Engineering, Bihar Engineering University (2024)
- Looking for a manual QA or junior QA role where I can learn on live projects

## How I write a bug report
Each bug has the same fields, so a developer can follow it without asking me anything:

1. **Title** - one line saying what is wrong and where
2. **Category and severity** - Functional, UI, Data, and a P0 to P4 level
3. **Steps to reproduce** - numbered, starting from the login page
4. **Expected and actual** - what should happen, what happened instead
5. **Evidence** - a screenshot or screen recording
6. **Environment** - browser, OS, viewport, date found
7. **Notes** - what I suspect but could not confirm

The empty template is in [`bug_report_template.md`](bug_report_template.md).

## Sample from a take-home exercise
I did a take-home QA exercise where I compared a web app clone with the original product, side by side in Chrome at 1280x960, and logged 19 bugs. The company and the app are private, so I do not share its links, screenshots or login details. [`sample_bug_tracker.csv`](sample_bug_tracker.csv) has five of the bug types I found, rewritten in general terms.

What I did in that exercise:
- Opened the original and the clone side by side and went through the same flow in both
- Checked form validation, navigation, buttons, counters and layout
- Marked each difference with a severity and a screenshot
- Left out things I could not back up with evidence, and wrote them under "suspected, not confirmed"

## Severity scale I use
| Level | Meaning |
|---|---|
| P0 | Blocker: app crash, data loss, login broken |
| P1 | Critical: major feature broken or severe UI breakage on a core screen |
| P2 | Major: wrong behaviour in a common flow, but the user can continue |
| P3 | Minor: small visual issue or an uncommon path |
| P4 | Trivial: cosmetic, typo, 1px spacing |

## Practice site report
[`saucedemo_bug_report.csv`](saucedemo_bug_report.csv) has three bugs I found on saucedemo.com, a public practice site. The screenshots (`S01_` to `S03_`) are in this repo.
