# Counterexample Hunter

Counterexample Hunter is a practice app for hunting counterexamples. Students probe "for every" claims in a Number Lab, test area versus perimeter claims with pairs of rectangles in a Rectangle Lab, and repair already broken claims in a Reverse Mode, where each proposed fix is checked on a sweep of values or rectangle pairs. Every claim in the app is stored as data plus a checker, so each test a student runs is evaluated directly rather than matched against typed answers.

Math 2201 Unit 7: Inductive and Deductive Reasoning (indicators 2.4, 2.3)

## How students use it

- Number Lab: pick a claim, type test values one at a time (integers, decimals, and simple fractions such as 3/4 or -5/2), and watch each test land in a running log as "claim holds" or "claim BREAKS". Use the hint button when stuck: it points at the kind of value to try, such as negatives, zero, or fractions. When a value breaks a claim, explain why one counterexample is enough and write the explanation in your own words. If a claim looks true, run at least 5 distinct sensible tests, then use the true verdict button and defend the verdict with a general reason.
- Rectangle Lab: set the length and width of two rectangles, watch the perimeters and areas update, and check the pair against the claim. A pair only tests the claim when the claim condition is met, and a pair that meets the condition but breaks the conclusion is a counterexample.
- Reverse Mode: read a broken claim and the counterexample that broke it, pick a repair (restrict the domain, add a condition, or weaken the conclusion), and verify it. The app tests the repair on a sweep of values or pairs, including the original counterexample.

Resolved claims, counterexample pairs, true verdicts, and verified repairs all fill in the Counterexample Record at the bottom of the page. Add notes, then print the record.

The printable record is the Section 3 portfolio evidence artifact for this unit. Print it from the record section at the bottom of the app and submit it to the assignment folder if your teacher asks for it.

## Tech note

Single HTML file, no dependencies, works offline. All logic runs on the page; nothing is sent anywhere and nothing is stored between visits.

GitHub topics when published: math-2201, inductive-deductive-reasoning, draft (draft removed after QA).
