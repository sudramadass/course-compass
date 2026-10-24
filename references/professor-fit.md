# Compare sections and instructors

Read the official term schedule first. A well-reviewed instructor who is not teaching an eligible section is
not a current enrollment option. Match the course, campus, instructor identity, session, and modality.

## Ask what matters to this student

Examples: structured lectures, frequent feedback, project-based assessment, accessible office hours, published
attendance expectations, or meeting times. Ask for preferences; do not diagnose a "learning style" or assume that
easy grading or a high overall rating fits everyone's goals.

Compare published syllabi and official section records. State when a syllabus is from a previous offering or
an assessment format is unknown. Describe tradeoffs rather than calling a professor objectively best or worst.

## Rate My Professors in this version

The feature is a link-out for manual student review. It has no API credentials, scraping dependency, or review
database. Do not advertise automatic ratings integration.

1. Search for profile links for the officially listed instructor and institution, or use a student-provided link.
   Use the visible search-result title/school information to check a match; do not treat it as proof if ambiguous.
2. Share the matching link without fetching the profile or copying review/rating data from search results.
   Do not construct a profile URL by guessing its numeric identifier. If no matching link is found, provide the
   homepage and the exact name/school to search manually.
3. Let the student read the site and optionally summarize what matters to them. Label their observations as
   student-provided, unverified review signals. If they supply scores, counts, or dates, keep that context.
4. Base any section recommendation primarily on eligibility, actual availability, constraints, and relevant
   published course information. Make review-based reasoning transparent and tentative.

The site's terms restrict automated access/scraping without permission:
https://www.ratemyprofessors.com/terms-of-use

If permitted automated data access becomes available, revise the Skill to document the source, permission,
authentication, freshness, and missing-data behavior before enabling it. An unofficial endpoint or a third-party
scraper package is not evidence of permission. The plan should remain useful without this optional source.

## Output pattern

"Section A fits your morning availability and lists a project component in the published syllabus.
Section B fits too, but I couldn't verify its assessment format. You can review the instructor profiles here."

Put actual verified links on their own lines. If the student supplies review observations, explain how they
affect the tradeoff, not a blanket judgment about the instructor. Missing reviews are neutral, not a penalty.
