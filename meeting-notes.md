---
title: "Team Meeting Notes"
---

# Team Meeting Notes

*Unit 6 team project.* I took the notes for five of the six team meetings and posted them to the team's task board. They are reproduced as written.

## Meeting 01 (8 August 2026)

[View on the team task board](https://github.com/julesrif/ML-Airbnb-Business-Analysis/issues/7)

Team kickoff for the Airbnb ML group project (Track 1): set up a GitHub Projects Kanban, agreed to propose business questions today and vote via Telegram, and decided to ask the lecturer tonight whether external datasets can be combined.

#### Project Approach

- Track 1 (classical ML): predict which factors most influence Airbnb price, extend from there

- Provided dataset too thin (~48k rows, no images); suggested idea is to cross with NYC open data

- Work async in parallel

#### Team Process

- Use GitHub Projects Kanban (created by Julio) for tasks and meeting tickets

- One reviewer per PR, 3-day review SLA; don't block on review, commit and move on

- Weekly meetings same slot; next meeting Sat 15th; notes via transcript + summary, no recording

- Clarify with lecturer tonight: external datasets allowed? and what 'compare across tracks' means

#### Decisions Made

- Pursue Track 1 (classical ML)

- Use GitHub Projects Kanban for task tracking

- Weekly meetings at this same slot; next one Saturday the 15th

- No meeting recordings; use transcript + summary instead

- PR review policy: one reviewer, 3-day turnaround, don't block progress

- Draft long-form (>1000 words) then narrow down

## Meeting 02 (15 August 2026)

[View on the team task board](https://github.com/julesrif/ML-Airbnb-Business-Analysis/issues/8)

Group project sync: reviewed Julio's baseline random forest PR, agreed on next steps for deep learning modeling, visualizations, and drafting the report outline. Team feels on track with three weeks to submission.

#### Baseline Model PR Review

- Julio's random forest PR merged as starting baseline, includes POIs and subway stations as variables

- Observation: overpriced samples dominate everywhere, not clustered as expected

- Approach: pick one model, tune parameters rather than brute-force comparing many

- Zee flagged need for an evaluation method inside the notebook

#### Next Work & Planning

- John-Jon to build visualizations per notebook version/hash in parallel with modeling

- Notebook size may force splitting submission into two parts

- Three weeks to submission; aim to finish coding this week, then writing + Turnitin sandbox review

#### Board & Docs

- New tickets: draft document outline (Zee), create Google Doc in shared Drive (Julio), clean dataset marked done

- Shared Drive folder already exists; John re-pinned link in group chat

#### Next Steps

- (Julio) Create Google Doc for report in shared Drive

- (John-Jon) Build visualizations per notebook version/hash as modeling progresses

- (John-Jon) Include visualization outputs in PR descriptions going forward

- (me) Update meeting 2 notes on the board

- (me) Create calendar invite for next Saturday, same time

- (Zee) Draft document outline (sections, structure) and share with team

- (Zee) Do literature review research and references

#### Decisions Made

- Baseline model ticket closed; Julio's random forest PR is the starting point

- Meeting facilitation rotates weekly

- Next meeting: same time next Saturday

## Meeting 04 (29 August 2026)

[View on the team task board](https://github.com/julesrif/ML-Airbnb-Business-Analysis/issues/34)

Team synced on final push for the UOE project: code review deprioritized, business question refined, and a mid-week checkpoint set before Saturday's final meeting.

#### Code Review & Scope

- Code normalization mostly done; further review deprioritized since code is barely graded

- Only ~1 week left, writing and visuals must not be blocked by code

- Business question reworded: drop 'strictly' since non-spatial features (reviews/month, availability) are used

#### Writing & Deliverables

- Outline done; most essay sections drafted, conclusion still outstanding

- Unify tone/style across sections after content is in

- Visuals uploaded to Google Drive; 5 selected for main doc, PR pending

- Open PR once code is cleaned up

- Literature/references to be topped up

#### Schedule

- Mid-week catch-up Wednesday Sept 2

- Target delivery next weekend, not Monday

#### Next Steps

- Clean up code and open PR for visuals; ping Telegram when dropped (by tomorrow night latest)

- Write conclusion section

- Run final style check (fonts, formatting) after content is finalized

- Remove 'strictly' from business question and refine spatial features wording

- Add a couple more literature sources

- Rewrite sections into a single unified tone/structure

- Submit final document to Turnitin

- Set up the Wednesday catch-up meeting

#### Decisions Made

- Deliver final document by next weekend, not Monday

- Code review effectively closed; no further deep review before submission

- Remove 'strictly' from the business question wording

- Final meeting next Saturday at usual time; mid-week catch-up Wednesday

## Meeting 05 (2 September 2026)

[View on the team task board](https://github.com/julesrif/ML-Airbnb-Business-Analysis/issues/35)

#### Report Discrepancies

* Cold-start framing conflicts with the random forest model using number of reviews and reviews per month.
* Baseline MAE of USD 47.34 and the 9.6% improvement claim are not present in the latest PDF output.
* Verified random forest MAE is USD 42.79; rerun the notebook so all figures match the latest output.

#### Notebook Merge & Rerun

* Move visuals imports to the top of the notebook.
* Finalise and merge the visuals PR into main.
* Rerun the full notebook after the merge.
* Share the updated PDF for review.

#### Submission Checks

* Rephrase the business question away from strict “cold start” framing toward starting-price prediction and geographic volatility.
* Submit the current draft to Turnitin as a sanity check.
* Do not include an appendix.
* Reread the report for styling and clarity.
* Address outstanding comments on the relevant section.

#### Next Steps

* Rerun the notebook after the merge and share the updated PDF.
* Submit the current draft to Turnitin to surface any issues.
* Copy the revised business question into the notebook.
* Address outstanding comments on the relevant section.
* Send a reminder to sync the revised business question into the notebook.
* Move lingering imports to the top of the notebook and finalise the visuals PR to main.
* Reword cold-start references throughout the report and conclusion to match the full-featured model.
* Reread the report for styling and clarity.

#### Decisions Made

* Drop the strict “cold start” framing and describe the approach as a full-featured pricing model for established listings.
* Do not include an appendix in the submission.
* Hold the next meeting on Saturday at the same time.

## Meeting 06 (5 September 2026)

[View on the team task board](https://github.com/julesrif/ML-Airbnb-Business-Analysis/issues/38)

#### Submission Plan

* Run the report through the Turnitin sandbox before final submission.
* Submit the final report once it has been validated.
* Include a PDF of the main notebook alongside the report as a safety net for reviewers.
* Resolve the conflicting pull request and rerun the relevant work before submission.

#### GitHub Repository Access

* Add the GitHub repository link to the cover page, directly under the module line, rather than including it in the references.
* Make the repository publicly accessible on Monday after the submission deadline.
* Request the professor’s GitHub username via LinkedIn if required.

#### Formatting Fixes

* Change the document font to Arial, size 12.
* Arrange the references in alphabetical order.
* Correct spacing and formatting inconsistencies in the reference list.

#### Next Steps

* Fix the reference order and spacing.
* Apply Arial 12 font consistently throughout the document.
* Run the report through the Turnitin sandbox.
* Submit the final report once the Turnitin check has been validated.
* Resolve the conflicting pull request and rerun the relevant work.
* Request the professor’s GitHub username via LinkedIn.
* Make the GitHub repository public on Monday after the deadline.
* Include a PDF of the main notebook with the final submission.

#### Decisions Made

* The GitHub repository link will be placed on the cover page under the module line.
* The repository will be made public on Monday after the submission deadline.
* A PDF of the main notebook will be submitted alongside the report.
