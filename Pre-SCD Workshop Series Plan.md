# Pre-SCD Online/Offline Workshop Series — Plan

## Context

The SBG core team at SDU wants to run a series of 5 workshops before the Student Community Day (SCD): 3 online AWS Workshop Studio sessions already scheduled by their presenters, a 4th online session still needing a date/topic, and a 5th in-person session at SDU sponsored by Elcore. This plan turns the loose list of names/dates/links into a concrete schedule with owners, a repeatable prep checklist for the online sessions, a dedicated checklist for the Elcore-sponsored offline session, and a task-distribution matrix based on each team member's strengths. This is an event-coordination plan, not a code change — the "implementation" is task execution by the 5 core team members.

## Confirmed schedule

| # | Date | Format | Presenter | Workshop | Status |
|---|------|--------|-----------|----------|--------|
| 1 | Thu, Aug 20, 2026 | Online | Assylbek | [AWS Workshop Studio lab](https://catalog.workshops.aws/workshops/76bc5278-3f38-46e8-b306-f0bfda551f5a/en-US) | Confirmed |
| 2 | Thu, Aug 27, 2026 | Online | Nurdaulet | [AWS Workshop Studio lab](https://catalog.workshops.aws/workshops/05554d54-07cc-483e-b810-d69f7d99b2ab/en-US) | Confirmed |
| 3 | Thu, Sep 3, 2026 | Online | Marzhan | [AWS Workshop Studio lab](https://catalog.us-east-1.prod.workshops.aws/workshops/cdbce152-b193-43df-8099-908ee2d1a6e4/en-US/aws-hosted) | Confirmed |
| 4 | Thu, Sep 10, 2026 | Online | Arslan | TBD — AI/data-science-leaning AWS Workshop Studio lab | **Open: Arslan to pick a lab by Aug 27** |
| 5 | Thu, Sep 24, 2026 | **Offline, SDU campus** | Adilet | Elcore-sponsored: AWS partnership + Elcore solutions showcase | Confirmed date; venue room + catering TBD |

Note: I could not render the content of the 3 Workshop Studio catalog links (JS-rendered pages returned no text to WebFetch/WebSearch) — each presenter should personally confirm module count, estimated duration, and whether it's self-paced-with-own-AWS-account vs. an "aws-hosted" lab needing AWS-provisioned temporary accounts (the 3rd link's `/aws-hosted` path suggests the latter — see Prep Step 1 below, this has a longer lead time).

## Cross-cutting roles (apply across all 5 sessions)

| Person | Strength                              | Standing role |
|---|---------------------------------------|---|
| **Nurdaulet** | Marketing specialist, incoming leader | Marketing & Promotion Lead for the whole series (Meetup listings, social posts, reminders) + external Partner Liaison to Elcore/Kateryna Gryshyna |
| **Adilet** | Senior, cloud-computing experience    | Technical Content Reviewer (dry-runs Assylbek/Nurdaulet/Marzhan/Arslan's decks before their date) + presenter of the offline Elcore session |
| **Assylbek** | Senior, DevOps/cloud experience       | Technical Content Reviewer (co-owns with Adilet) + presenter #1 |
| **Marzhan** | Data analytics + event organization   | Event Ops Lead (registration tracking, feedback surveys, budget/expense tracking) + presenter #3 |
| **Arslan** | Data science + event-org support      | Event Ops support (co-owns with Marzhan) + attendance/feedback reporting after each session + presenter #4 |

Rationale: marketing and technical-review load is spread across people who are *not* presenting that week, so no one both presents and runs logistics for their own session.

## Standard checklist per online workshop (repeat for #1–#4)

**T–1 week (by the Thursday before)**
- [ ] Presenter copies the official SBG deck from [`01- Creative Assets _ Fonts, Icons, Etc./Presentation Template/AWS_StudentBuilderGroups_PPTTemplate_Final .pptx`](<01- Creative Assets _ Fonts, Icons, Etc./Presentation Template/AWS_StudentBuilderGroups_PPTTemplate_Final .pptx>) and builds their slides on it, so branding stays consistent across the series
- [ ] Presenter confirms which module(s)/hands-on labs fit the ~1.5–2hr slot (trim if the full Workshop Studio lab runs longer)
- [ ] Presenter confirms account-access model: self-service AWS account vs. AWS-provisioned event access code. If the latter, request codes from the AWS SBG program contact **now** — provisioning can take several days
- [ ] Technical reviewer (Adilet/Assylbek, whichever isn't presenting) does a dry-run of the deck/lab with the presenter
- [ ] Nurdaulet publishes the Meetup.com listing (date, time, agenda, prerequisites, streaming link) + opens registration
- [ ] Marzhan/Arslan set up the Attendee Info Form (reuse `Student Community Days/Attendee Info Form Template.xlsx`) and feedback survey link
- [ ] Nurdaulet (or presenter) schedules the Zoom meeting: enable **cloud recording** in advance settings, set a waiting room or passcode, assign host (presenter) / co-host (a non-presenting core member, for chat & Q&A moderation), and confirm the account's time-limit tier covers the full 1.5–2hr slot
- [ ] Add the Zoom join link to the Meetup listing and Attendee Info Form once scheduled

**T–2 days**
- [ ] Nurdaulet sends reminder email/social post with join link and any setup-ahead-of-time instructions (e.g., "create your AWS account before the session")
- [ ] Presenter test-runs Zoom screen share (share the specific window, not full desktop) and mic/audio from the actual room/setup they'll use on the day

**Day-of**
- [ ] Host joins Zoom 10–15 min early: start cloud recording immediately, admit attendees from the waiting room, confirm screen share works
- [ ] 2–3 min SBG intro segment (mission, Meetup/AWS Builder Center QR — reuse assets from `Student Community Days/Student Community Day - AWS Builder Center QR Code Sign.pptx`)
- [ ] Co-host manages chat/mutes and unmutes attendees during live Q&A
- [ ] Live workshop delivery + Q&A
- [ ] Feedback form link dropped in Zoom chat before people drop off
- [ ] Stop recording at the end; confirm in Zoom that cloud recording finished processing before closing the meeting

**T+2 days after**
- [ ] Host retrieves the Zoom cloud recording, trims dead air at start/end if needed, and uploads it (e.g., YouTube unlisted/public)
- [ ] Nurdaulet posts thank-you + uploads recording/slides
- [ ] Delete the Zoom cloud recording from Zoom's storage once safely uploaded elsewhere (frees the account's storage quota for the next session)
- [ ] Marzhan/Arslan log attendance count and feedback summary; short debrief note (what worked, what to fix for the next one)

## Offline Elcore workshop (Sep 24, SDU campus) — dedicated checklist

**Content**
- Adilet presents solo (confirmed) — covering: what Elcore does, how Elcore partners with AWS, and Elcore's solution(s), on top of a technical segment Adilet leads himself.
- Because Adilet presents Elcore's content without their rep in the room, **get written material from Elcore, not verbal notes** — a company one-pager, approved slide(s)/logo files, and explicit sign-off on what's presented as "their story."

**Elcore coordination (owner: Nurdaulet, as Partner Liaison)**
- [ ] Request from Kateryna Gryshyna: brand guidelines (logo usage, colors, do's/don'ts), an approved slide or blurb describing the AWS partnership and their solution(s), and confirmation of what Elcore wants highlighted
- [ ] Confirm rollup banner: does Elcore ship it to SDU or does someone pick it up? Who returns it after the event?
- [ ] Confirm expectations for acknowledgment (logo on event slides/Meetup page, verbal thank-you, social media tag) — balance this against the Playbook's "learning value first" guidance so it doesn't read as a pure vendor pitch
- [ ] Confirm Elcore's own reporting needs — do they want photos/attendance numbers back after the event for their sponsorship records?

**Logistics (owner: Marzhan, with Arslan support)**
- [ ] Book SDU room (capacity to match expected headcount; confirm AV/projector/mic availability)
- [ ] $150 budget split: treats (catering appropriate for headcount, note dietary restrictions per Playbook's inclusivity guidance) + Elcore rollup banner logistics (assume banner itself is provided by Elcore free — budget covers setup/transport if needed, otherwise budget goes entirely to treats)
- [ ] Keep all receipts — required for the post-event AWS expense report (`StudentBuilders@amazon.com`, due 14 days after event) and likely for Elcore's own reporting
- [ ] Registration via Meetup + Attendee Info Form, same as online sessions
- [ ] Signage: welcome sign, agenda sign, directional signage to the room, rollup banner placement near entrance/stage

**Content review (owner: Assylbek, as the technical reviewer not presenting that day)**
- [ ] Dry-run Adilet's deck 1 week out, checking the Elcore segment doesn't overrun and the technical segment is scoped for the room's AV setup

**Timeline**
- T–4 weeks (now–Aug 27): Nurdaulet opens Elcore coordination; Marzhan starts SDU room booking
- T–2 weeks (Sep 10): Elcore materials + banner logistics confirmed; budget finalized
- T–1 week (Sep 17): Adilet's deck dry-run with Assylbek; registration opens
- T–2 days (Sep 22): reminder push; catering order placed
- Day-of (Sep 24): run standard day-of checklist (above) + banner setup + treats
- T+2 weeks (Oct 8, aligned with Playbook's 14-day expense deadline): expense report submitted, thank-you sent to Elcore/Kateryna with photos and attendance numbers

## Open items to close before execution

- Arslan needs to pick his AWS Workshop Studio lab (target: by Aug 27, so there's 2 weeks of lead time before his Sep 10 slot)
- SDU room booking for Sep 24 not yet confirmed — Marzhan to lock in this week
- Whether Elcore ships the rollup banner or someone must pick it up — pending Kateryna's reply
