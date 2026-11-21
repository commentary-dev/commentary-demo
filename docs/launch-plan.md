# Launch Plan

## Phase 1: Demo shape

- Finalize the sample pull request content.
- Add homepage entry points for the demo review.
- Document the reset mechanism for operators.

## Phase 2: Visitor confidence

- Validate that anonymous users can read the sample review.
- Confirm that authenticated users can add comments and submit a review as themselves.
- Tighten the review-page copy so visitors understand they are in a resettable sample workspace.
- Align the demo documents with the exact language used on the homepage.
- Retire the separate FAQ and fold the essential answers into the launch narrative.

## Readiness checklist

- The pull request contains at least three Markdown files.
- The commit list includes structural document changes, not only word edits.
- The review page clearly points back to the visitor's own repository flow.
- The launch summary matches the migration notes and traceability appendix.

## Risks

- If the fixture PR accumulates too many comments, first-time visitors will see noise instead of the product shape.
- If the PR contains only one commit, the change-set picker will not demonstrate Commentary's diff tooling.
- If the content sounds synthetic, the demo will feel like a test harness instead of a real workspace.

## Operator note

When the reset workflow closes and recreates the PR, visitors should still land on the same `/demo` entry point instead of needing the raw GitHub URL.
