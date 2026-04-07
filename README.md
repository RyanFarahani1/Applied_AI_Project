# Image Captioning Dataset (Visual Assistance)

This repository contains the **dataset files** I used for an image-captioning project aimed at assisting visually impaired users.

## What’s in this repo

- `visuallyimpair/visual_dataset/`: image files
- `visuallyimpair/visual_text/`:
  - `visual.token.txt`: image → caption pairs
  - `visual.trainImages.txt`: train split filenames
  - `visual.testImages.txt`: test split filenames

## How to use

Typical training pipeline:

1. Load the image files from `visuallyimpair/visual_dataset/`
2. Parse `visual.token.txt` to build (image, caption) examples
3. Use `visual.trainImages.txt` / `visual.testImages.txt` for splits

## Notes

- This repo intentionally focuses on **data + split definitions**. Model/training code lives in separate project repositories.

