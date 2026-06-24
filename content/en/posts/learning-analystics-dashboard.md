---
title: "Learning Analytics Dashboard | R Shiny, Power BI"
date: 2026-06-24
slug: "learning-analytics-dashboard"
tags: ["R", "Shiny", "Learning Analytics", "Data Visualization", "Portfolio"]
---

## Project Context

I first developed this dashboard as a Power BI prototype to practice BI reporting, KPI design, interactive filtering, and dashboard layout. Since public Power BI embedding usually requires organizational publishing access, I recreated the dashboard in R Shiny so it could be shared publicly and used interactively.

This project demonstrates both Power BI dashboard design skills and the ability to translate the same analytical workflow into a custom R Shiny web application.

## Summary

This interactive R Shiny dashboard explores student engagement, satisfaction, assessment performance, and completion patterns using a synthetic learning analytics dataset.

The dashboard allows users to filter by academic term, faculty, course modality, and international student status. It includes KPI cards, faculty-level satisfaction comparisons, modality-based assessment performance, course-level engagement and performance analysis, and a searchable data table.

<div style="
  width: 100vw;
  margin-left: calc(50% - 50vw);
  margin-right: calc(50% - 50vw);
  padding: 0 16px;
  box-sizing: border-box;
">
  <iframe
    src="https://ashleyym.shinyapps.io/learning-analytics-dashboard/"
    title="Learning Analytics Dashboard"
    style="
      width: 100%;
      height: 950px;
      border: 1px solid #ddd;
      border-radius: 8px;
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
