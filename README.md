# Denton Fire: Recruiting and Community Answers

Live site: **https://dentonfire.github.io/Answers/**

Straight answers to the questions the Denton Fire Department recruiting and Community Risk Reduction inbox gets most: hiring, certifications, the Civil Service exam, hiring steps, ride-alongs, Explorer Post 1291, and event requests. Link it in the out-of-office auto-reply so people can find answers on their own.

## What's on the page

- Key facts: next exam date, registration deadline, starting salary, age range
- Buttons for exam registration, the [Extra Points page](https://dentonfire.github.io/Extra-Points/), and the [recruit list](https://www.readytoserve.io/denton-fire)
- A search box that filters the answers as you type
- Questions grouped by topic, plus a contact table
- A share button (bottom right) with a QR code and copy-link

## Updating it

Everything is in `index.html`. It uses Tailwind from a CDN and the same navy, red, and yellow theme as the other DentonFire tools. There is no build step.

1. Open `index.html` on GitHub and click the pencil icon, or clone the repo.
2. Each answer is a `<details>` block with a `<summary>` (the question) and a `<div class="a">` (the answer). Copy an existing block to add a new question.
3. Commit to `main`. GitHub Pages redeploys in a minute or two. Hard refresh to check it.

### Update twice a year (CRRO Manual 9.1.1 and 10.2)

**When registration opens (October):**
- Key facts at the top: exam date, registration deadline, salary
- The registration link (search the file for `smartsheet.com`; it appears in the button, the exam section, and the contact table). Each exam year gets a new Smartsheet form.
- The "When and where is the next exam?" and "How do I register?" answers
- The "Last updated" date in the footer

**When registration closes:**
- Replace the registration button and links with the recruit list, and change the "How do I register?" answer to say registration is closed

Add a question any time the same question reaches the inbox more than once. Keep the facts in step with the Recruiting Inbox Reply Rules and CRRO Manual Section 8.2.

## Writing style

Short and direct. Answer the question in the first line, including when the answer is no, then give the next step. No em dashes. The City of Denton's official pages and the Notice of Civil Service Examination control if anything here differs.

## Contact

Community Risk Reduction Officer (recruiting, public education and events, Fire Explorers, Fire Camp, Citizens Fire Academy, Clowns on Fire): firerecruiter@cityofdenton.com
Fire Administration: 940-349-8840
