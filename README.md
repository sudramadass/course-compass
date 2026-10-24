# Course Compass

A Cubbie Skill that turns a student's career goal into a university-specific course plan, with official sources,
prerequisite checks, and section comparisons.

Try: "I want to become a machine learning engineer. Help me choose next term's classes at my university."

## What it does

- Researches the student's university on demand, across majors, campuses, and academic calendars.
- Separates degree requirements, career suggestions, prerequisite eligibility, and actual term offerings.
- Uses course history and preferences to propose a realistic load and explain tradeoffs.
- Compares officially listed sections and offers Rate My Professors links for manual student review.
- Produces a detailed planning document when needed; optionally remembers preferences or creates approved reminders.

Coverage depends on accessible official information. When a catalog, schedule, or degree audit is unavailable,
Cubbie asks for relevant documents and marks the plan provisional. It does not guarantee enrollment eligibility,
future offerings, graduation dates, or career outcomes. Rate My Professors data is not automatically fetched.

## Install on Cubbie

Publish this folder as a public GitHub repository, or a folder inside one. Text that repository/folder link to
your Cubbie, review its install prompt, and approve it. Start the course-planning request in a new message.
There is no package installation, API key, or new account required for public-source research.

To update after a fix, push the change and text the same branch or default-repository link again.

## On-phone test checklist

1. Text the published link, approve installation, then send the example request above in a new message.
2. Provide school/program, catalog year, target term, course history, and credit preferences as Cubbie asks.
3. Check that it opens official sources and shows prerequisite and term-offering uncertainty beside each course.
4. Ask for a professor comparison. Expect actual target-term instructors and manual-review links, not invented ratings.
5. Give a course with an unmet prerequisite. Expect a blocked/later option, not immediate enrollment advice.
6. Try another university. Expect new institution-specific sources rather than reused course codes or policies.
7. Try an unpublished term or login-only schedule. Expect a candidate list and one request for missing information.
8. Ask for a reminder. Expect a specific time/time zone and approval before creation; verify it actually arrives.
9. Ask to add a schedule to Calendar. Expect a preview and approval before any events are written.
10. If you agree to saved preferences, return later and confirm they are reused and current offerings are rechecked.
11. Send a near-miss: "Quiz me on this week's lecture." Expect ordinary study help instead of course-selection intake.

## Structure

- `SKILL.md`: complete Cubbie workflow and reply rules.
- `references/research-guide.md`: source discovery, prerequisite logic, and missing-data behavior.
- `references/career-fit.md`: career-to-topic research starting points.
- `references/professor-fit.md`: section comparisons and manual review links.
- `assets/plan-template.md`: detailed planning-document fields.

This Skill creates plans and registration links. It does not enroll, drop, swap, or pay for classes.
