# Weird October

One weird little website a day, all 31 days of October, all in one place.

The homepage is a calendar. Hover a day to flip its card and see that day's
theme; click it to open that day's standalone page.

Built for [Weird Web October](https://weirdweboctober.website) — a month-long
challenge to make one small, weird website per day.

## Live site

`https://natagapova.github.io/weird-october/`

## Progress

| Day | Theme         | Status |
|-----|---------------|--------|
| 1   | Reveal        | ✅ |
| 2   | Spark         | ✅ |
| 3   | Fake          | ✅ |
| 4   | Plastic       | ✅ |
| 5   | Sheet         | ✅ |
| 6   | Analog        | ✅ |
| 7   | Organic       | ✅ |
| 8   | Skeumorphism  | ✅ |
| 9   | Spicy         | ✅ |
| 10  | Layers        | ✅ |
| 11  | Stuck         | ✅ |
| 12  | Pointy        | ✅ |
| 13  | Scratch       | ✅ |
| 14  | Origami       | ✅ |
| 15  | Wooden        | ✅ |
| 16  | Instant       | ✅ |
| 17  | Branching     | ✅ |
| 18  | Geometric     | ✅ |
| 19  | Distorted     | ✅ |
| 20  | Undefined     | ✅ |
| 21  | Illusion      | ✅ |
| 22  | Skeletons     | ⬜ |
| 23  | Incognito     | ⬜ |
| 24  | Collage       | ⬜ |
| 25  | Ascending     | ⬜ |
| 26  | Net           | ⬜ |
| 27  | Spiral        | ⬜ |
| 28  | Smooth        | ⬜ |
| 29  | The End       | ⬜ |
| 30  | Pastel        | ⬜ |
| 31  | Spooky        | ⬜ |

## Structure

```
index.html        → calendar homepage
days/
  01/index.html    → Day 1, self-contained
  02/index.html    → Day 2, self-contained
  ...
```

Each day's page is a single self-contained HTML file with its own inline
CSS/JS — no shared build step, no dependencies. That's deliberate: every day
can look and behave completely differently from the others.
