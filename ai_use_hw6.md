# AI Use Disclosure

**Temi Ilori** CIS 4374, Information Systems Project Management, Section 19148 Homework 6, ParkHere Software Requirements Specification v0.6 October 13, 2026

---

## Summary

I used Claude (Anthropic, through claude.ai) as a drafting and checking partner for this week's project update. The slide for this week said there were no new chapters and that everything should be up to date, so the work was reviewing each existing section and making them agree with each other. Claude audited the whole document, drafted the changes into it, rebuilt the Gantt chart, recomputed the budget, and checked the result with a script. Claude also drafted this week's video script and this disclosure. I am submitting the document, the script, and this disclosure as my work for the week.

Prompts below are pasted from my chats. I cleaned up spelling and punctuation so they read clearly. What I asked for is unchanged.

---

## Instance 1\. Auditing the document and drafting the updates

### Tool

Claude (claude.ai)

### What it was used for

I shared this week's slide, which says to update the SRS, user stories, WBS, timeline and Gantt charts, backlog, sprints and Jira or Trello screenshots, risks and risk register, communication plan, roles, cost plan, and RACI matrix. Claude read the whole document, listed places where sections disagreed with each other, and drafted the fixes.

- User stories and non-functional requirements were added inside Section 8, since no new chapters were allowed. Three use cases (password reset, operator sign-in, and refund and dispute review) were added because the WBS and backlog already contained that work.  
- The WBS got two components, Testing, Security and Launch (5.0) and Project Management (6.0), because testing, penetration testing, and project management were in the schedule and cost plan but not in the WBS.  
- The timeline table and Gantt chart were rebuilt. Facility onboarding moved to September 15, incremental QA starts September 29, and the stretch reports became their own phase.  
- The backlog went from 52 to 60 cards and a six-sprint plan was added as tables.  
- Risks R21 to R23 were added and seven existing risk responses were updated. The communication plan, roster, and RACI matrix were updated to match.  
- The mapping lead now stays through November 30 and a load testing service was added, which moved the total budget from \$459,485 to \$472,421.  
- A reasons-for-changes table was added as Section 17.1, because the video needs to explain what led to each decision.

### Prompts

> I sent the Homework 6 slide ("Homework: Project Update Instructions") as an image with no typed message.

### What I kept and what I changed

I kept the changes Claude drafted and submitted them as written. The non-functional requirement numbers (3 seconds, 99.5 percent availability, 1,000 users, 5 minutes) and the choice to keep the mapping lead through November 30 are planning assumptions that came from Claude's draft.

---

## Instance 2\. Handling the Trello board

### Tool

Claude (claude.ai)

### What it was used for

Claude first tried to open my Trello board to update it. The browser it used was not signed in to Trello, and Claude does not enter passwords. My Trello premium trial had ended, so I asked Claude to work around not changing the board.

### Prompts

> "Okay so my Trello free premium already ended. Can we work around not changing the board?"

### What I kept and what I changed

The board was not changed. The two Trello screenshots in Section 11 are labeled as version 0.3, and the current backlog and sprint plan are tables in Sections 11.1 and 11.2.

---

## Instance 3\. Video script

### Tool

Claude (claude.ai)

### What it was used for

Drafting the script for this week's stakeholder video. Claude wrote a first version, then shortened it, then rewrote it in plainer language so stakeholders listening can follow it.

### Prompts

> "Give me a shorter video script, more compact but within the time frame."  
>   
> "The script is not so easy to understand if stakeholders are listening."

### What I kept and what I changed

I am using the final plain-language version as an outline for the video.

---

## Instance 4\. This disclosure

### Tool

Claude (claude.ai)

### What it was used for

Drafting this disclosure file, including a version with no blanks left for me to fill in.

### Prompts

> "With the AI use MD for this week, could I have the updated version so I don't have to fill anything in before submitting and everything is ready to submit?"

### What I kept and what I changed

I am submitting this file as written.

---

## Verification

Most of this week's content is planning assumptions inside a fictional project, so there is little to check against the outside world. The checks below were run by Claude with a script, and I did not repeat them by hand.

- Every working day count, hour total, labor cost, non-labor total, monthly cashflow figure, contingency amount, and cumulative total was recalculated from the finished document, and all of them matched. Total labor is \$406,910 for 4,978 hours, non-labor is \$22,564, contingency is \$42,947, and the total is \$472,421. The change from last week is \$10,260 for the mapping lead, \$1,500 for load testing, and \$1,176 in contingency, which adds up to the \$12,936 difference from \$459,485.  
- Every RACI row has exactly one Accountable and at least one Responsible, across 18 rows.  
- All 21 use cases each have one user story. The sprint cards add up to 60, which is the 52 original cards plus 8 added. The risk register has 23 risks with at least four in each category. Phase durations match their start and end dates, and every person's start date matches a phase start in Section 10\.  
- Sections 2 through 7 are unchanged from last week, confirmed by a text comparison. The table of contents page numbers were checked against a rendered copy of the document and may shift slightly when opened in Word.  
- The pay rate and app store fee sources are unchanged from last week.