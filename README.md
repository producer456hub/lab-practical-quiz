# Lab Practical Quiz

Multiple-choice quiz and flashcards for anatomy lab practical prep.

**Live site:** https://producer456hub.github.io/lab-practical-quiz/

## What it does

- Quiz mode: shows a lab image with one structure marked, pick the correct name from 4 multiple-choice options
- Flashcard mode: same image with the structure marked; click to flip and reveal the answer
- Source labels are masked, leader lines kept intact so you trace from the marker to the structure
- 169 questions across 18 cropped anatomy views

## Run locally

The app uses `fetch()` for the dataset, so it needs to be served over HTTP (browsers block `file://` fetches). From this folder:

```
python -m http.server 8000
```

Then open http://localhost:8000/
