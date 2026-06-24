---
title: "Learning Analytics Dashboard | R Shiny"
date: 2026-06-24
slug: "learning-analytics-dashboard"
tags: ["R", "Shiny", "Learning Analytics", "Data Visualization", "Portfolio"]
---

I built an interactive R Shiny dashboard to explore student engagement, satisfaction, assessment performance, and completion patterns using a synthetic learning analytics dataset.

The dashboard allows users to filter by academic term, faculty, course modality, and international student status. It includes KPI cards, faculty-level satisfaction comparisons, modality-based assessment performance, course-level engagement and performance analysis, and a searchable data table.

<div style="
  width: 100vw;
  margin-left: calc(50% - 50vw);
  margin-right: calc(50% - 50vw);
">
  <iframe
    src="https://ashleyym.shinyapps.io/learning-analytics-dashboard/"
    title="Learning Analytics Dashboard"
    style="
      width: 100%;
      height: 950px;
      border: 0;
      display: block;
    ">
  </iframe>
</div>

If the dashboard does not load inside this page, open it here:

[Open interactive dashboard](https://ashleyym.shinyapps.io/learning-analytics-dashboard/)

## Tools

R, Shiny, bslib, dplyr, ggplot2, DT, data visualization, learning analytics, program evaluation

## Key Features

- Interactive filters for term, faculty, modality, and student subgroup
- KPI cards for total students, average satisfaction, and completion rate
- Faculty-level satisfaction comparison
- Assessment performance by course modality
- Course-level engagement and assessment visualization
- Searchable filtered data table

## Dataset Note

This project uses synthetic data created for portfolio demonstration purposes. It does not contain real student records.
