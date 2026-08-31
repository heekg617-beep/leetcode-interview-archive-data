# LeetCode Interview Archive Data

Public static JSON data repository for the LeetCode Interview Archive website.

## Structure

data/
  interviews/
    index.json
    502.json
    42.json
    ...

## Workflow

- Each `{problem_id}.json` is the TRACKER_UPDATE output from a completed ChatGPT coding interview.
- The frontend fetches `index.json` for the archive list.
- The frontend lazy-loads `{problem_id}.json` when an interview is opened.
- Add new interviews by committing one JSON file and updating `index.json`.

## GitHub Pages

Recommended visibility: Public.

After enabling GitHub Pages, the frontend base URL can be:

https://<username>.github.io/leetcode-interview-archive-data/data/interviews

Do not commit secrets or private personal information.
