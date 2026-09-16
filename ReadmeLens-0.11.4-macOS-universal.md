ReadmeLens v0.11.4

Fixes table text overlapping the rows below it.

- Any table with a cell long enough to wrap drew its extra lines on
  top of the next row, which made prose-heavy tables unreadable —
  tables now measure their rows at the width the cells actually get
- Wide tables still scroll sideways on their own, and printed tables
  now shrink to the page instead of running off it

