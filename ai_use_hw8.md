# AI Use Disclosure

**Temi Ilori**
CIS 4374, Information Systems Project Management, Section 19148
Homework 8, ParkHere Software Requirements Specification v0.8 and a post mortem
November 5, 2026

---

## Summary

I used Claude (Anthropic, through claude.ai) as a drafting, research, and checking partner for this week's assignment, which was a project closure report at the end of my project document and a separate post mortem of a failed project or technology that was not discussed in class. Claude wrote the closure report from the facts already in my project document, chose and researched the failed project for the post mortem, built both documents, updated the rest of the project document to match, and checked the result with a script. Claude also drafted this week's video script and this disclosure. I am submitting the document, the post mortem, the script, and this disclosure as my work for the week.

The only thing I sent Claude was the slide below. I did not type any other prompt for this assignment.

---

## Instance 1. Project closure report in the project document

### Tool
Claude (claude.ai)

### What it was used for
I shared this week's slide, which says to prepare a project closure report at the end of the project document, marked as internal, with a 1 to 2 minute video, containing an executive summary, achievements and shortfalls, lessons learned, and recommendations for future projects. Claude added it as Section 22 with an INTERNAL banner and its own INTERNAL header and footer, plus a closure checklist for the delivery phase. It also bumped the document to version 0.8, added the revision history entry and a reasons table (Section 20.3), added one definition, updated the purpose, and regenerated the table of contents.

ParkHere is a plan and nothing has been built, so Claude did not invent launch results, actual spend, or defect counts. The report is written about the planning work and says so at the start. The achievements, shortfalls, and lessons come from facts already in the document, such as the Trello board still showing version 0.3, the unsigned charters, the app store risk R24 being found in version 0.7, and the rework in version 0.6. The one budget change is the one already recorded in Section 20.1. Which items are shortfalls, the lessons, and the recommendations are Claude's judgment based on that history.

### Prompts
> I sent the Homework 8 slide as an image with no typed message. The slide says to prepare a project closure report at the end of the project document, marked as internal, including a 1 to 2 minute video, containing an executive summary, achievements and shortfalls, lessons learned, and recommendations for future projects, and to research and create a post mortem for a failed project or technology of my choice that was not discussed in class, as a separate document and not in the project document.

### What I kept and what I changed
I kept the closure report as Claude drafted it. The dates in the closure checklist, such as November 9 for sponsor sign off and December 4 for the go/no-go decision, are Claude's choices based on the sprint review dates and the end of launch prep in the plan.

---

## Instance 2. Post mortem of the TSB Bank 2018 IT migration

### Tool
Claude (claude.ai), including its web search and web page reading

### What it was used for
Claude chose the failed project, which was TSB Bank's 2018 move of about five million customers to a new banking platform, and I did not choose it. Claude searched for sources, read the pages, and wrote a separate Word document with a summary, background, timeline, impact, causes, what went well, lessons, a section on what it means for ParkHere, a note on the evidence, and a source list. I do not know whether TSB was discussed in class, so I have not confirmed that it was not.

### Prompts
> Same message as Instance 1, the Homework 8 slide.

### What I kept and what I changed
I kept the post mortem as Claude drafted it. The section on what this means for ParkHere is Claude's judgment and connects the lessons to risks R05, R08, and R24 and to the charter.

---

## Instance 3. Video script and this disclosure

### Tool
Claude (claude.ai)

### What it was used for
Drafting the script for this week's video, in plain language with screen sharing cues, and drafting this disclosure file.

### Prompts
> Same message as Instance 1, the Homework 8 slide.

### What I kept and what I changed
I am using the script as an outline for the video. I am submitting this file as written.

---

## Verification

The checks below were run by Claude with a script and by reading the sources, and I did not repeat them by hand.

**Project document**
- The budget figures in Section 22 match the cost plan. Labor is $406,910, non-labor is $22,564, contingency is $42,947, and the total is $472,421. The one budget change of $12,936 (from $459,485), or 2.8%, matches Section 20.1.
- The counts in Section 22 match the document. There are 21 use cases, 21 user stories, 6 non-functional requirements, 11 schedule phases, 60 backlog cards, 24 risks that are all Open, 14 people, 19 RACI rows, and 10 stakeholders.
- The dates and risks cited match the plan. R08 starts QA on September 29, R19 moves onboarding to September 15, and R24 submits on December 1. The checklist dates of November 9, November 30, and December 4 are phase end dates in Section 10.
- Section headings run from 1 to 22 in order, every section reference points to a section that exists, and the table of contents page numbers match a rendered copy. They may shift slightly in Word, so update the field there once.
- Sections 2 to 19 are unchanged from version 0.7, apart from the purpose, one definition, and the title date.
- Section 22 has no em dashes or colons, and the INTERNAL header and footer are only on the Section 22 pages.

**Post mortem**
- Each figure was taken from a page Claude opened. The fine amounts and redress come from the Financial Conduct Authority release. The cost breakdown of £330.2 million (125.2 + 49.1 + 33.5 + 122.4, all in millions of pounds) adds up, and the loss before tax comes from the press coverage of TSB's 2018 results. The review findings come from press coverage of the report and from TSB's own summary page.
- Claude could not open the full 262-page Slaughter and May report, because TSB's PDF would not load. The post mortem says this in Section 9. Points that only the press reports, and that TSB disputes, are marked as such in the text.
- Different outlets give different total costs. The post mortem uses TSB's reported 2018 figure of 330.2 million pounds and notes that later press coverage put it near 370 million pounds.

---

## Sources

- Financial Conduct Authority, TSB fined £48.65m for operational resilience failings, fca.org.uk.
- TSB, Slaughter and May report page, tsb.co.uk.
- Slaughter and May, Independent Review of TSB's 2018 migration to a new IT platform, slaughterandmay.com.
- Computer Weekly, TSB programme pulled apart in report on IT meltdown, computerweekly.com.
- ITPro, TSB's IT disaster pinned on big bang approach to migration, and TSB bank fined £48 million over botched IT upgrade programme, itpro.com.
- Finextra, TSB and Banco Sabadell slammed in meltdown post mortem, finextra.com.
- Silicon UK, Data centre test omission blamed for TSB IT fiasco, silicon.co.uk.
- The Register, TSB 2018 full-year losses, theregister.com.
- Credit Strategy, IT meltdown cost TSB £330m, full year results show, creditstrategy.co.uk.
- Reuters via Business Standard, TSB CEO leaves bank after IT fiasco batters brand, business-standard.com.
