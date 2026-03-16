# Video-Conversion-Scripts

Before importing, convert files with the script named 'Converter'. File sizes will be large at this step but it will be easy to edit with.

After editing has concluded, run the Archiver. You'll get a roughly ~20x reduction from file sizes at the editing stage. All metadata is kept.

If editing a film, run 'Film-Converter". The script will delete itself and the original compressed film.

**File structure required:**

```
Footage >
  1 <
  2 <
  3 <
  4 <
  5 <
  Unconverted (Place all footage from camera here.) >
    1 <
    2 <
    3 <
    4 <
    5 <
    Converter.py
```
