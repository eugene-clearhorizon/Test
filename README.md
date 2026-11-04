# Riverlands Youth Connect evaluation report

This is a short, interactive evaluation report for a made-up youth mentoring program. It's a working example of how an evaluation report could look as a web page, with the evidence sitting next to the findings it supports. Everything in it, from the program to the numbers and quotes, is invented.

## What's in the report

The program in the example is Riverlands Youth Connect, a 12-month mentoring program for young people aged 14 to 17 across three Riverina sites (Wagga Wagga, Griffith and Albury). The report follows a simple order: a summary, then one section for each key evaluation question (KEQ), then an overall judgement.

- **KEQ 1 (Outcomes)** compares connectedness and wellbeing scores at the start and end of the program. A toggle switches between the two measures, and clicking a site filters the quotes further down the page.
- **KEQ 2 (What helped and hindered)** sets out three findings. Each one keeps what was observed, how it was interpreted and the judgement made apart, and gives a rating for how strong the evidence is. You can expand the evidence behind each finding.
- **Qualitative evidence** has a table showing how many interviewees at each site raised each of four themes. Clicking a theme brings up its quotes and a link back to the finding it relates to.
- **KEQ 3 (Worth continuing?)** gives the overall judgement and notes the main limits of the evidence.

## Using it

The whole report is one file, `riverlands-eval.html`. Open it in a browser and it works without any build step or install. It loads fonts from Google Fonts, so the type will fall back to system fonts if you're offline. It adjusts to light and dark mode and works at phone width.

To reuse it with real data, most of the content lives in two places. The written text (summary, findings, judgement) is plain HTML in the body. The chart scores, interview counts by theme and the quotes are in the `sites`, `themes` and `quotes` arrays at the top of the script near the end of the file. If you change the number of interviews at a site, update `ivN` as well so the table's denominators stay right.

## A note on the data

The interview counts in the theme table were invented for this example and kept consistent with the figures quoted in the findings. Treat all of it as placeholder content.
