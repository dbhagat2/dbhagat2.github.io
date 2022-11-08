---
name: Assignment 10
tools: [Python, HTML, vega-lite]
image: assets/pngs/buildings.png
description: This is Assignment 10 by Dhruvi, Sheny, Powell and Neil
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

<vegachart schema-url="{{ site.baseurl }}/assets/json/Viz1.json" style="width: 80%"></vegachart>

# Write Up for Viz1

The visualization 1 is created to demonstrate the maximum and minimum floors of each constructed year in building dataset. In the chart, I encode the 'Year Constructed' as ordinal data type since year is discrete ordered number and encode 'Total Floors' as quantitative data type. As for other design choice, I use blue for the maximum total floors and red for the minimum total floors.

<vegachart schema-url="{{ site.baseurl }}/assets/json/Viz2.json" style="width: 80%"></vegachart>

# Write Up for Viz2

The visualization 2 was created to describe the relationship of "Agency Name" and "square footage" as well as "year acquired" and "square footage" of the buildings. This visualization is a dashboard with a heatmap on the left and a bar plot on the right. As for design choices, "square footage" is a quantitative value, "Agency Name" is a discrete unordered category, and the "year acquired" is a discrete ordered quantity which makes it ordinal. I change the encoding of “year acquired“ from quantitative to ordinal to make it work with Altair. The color choices in this visualization is by default and if you make a selection on the heatmap, the bar plot will transform. Therefore, we can see the relationship of the agency, the square footage, and the year acquired of the buildings.

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_bcubcg_fall2022/main/data/building_inventory.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/dbhagat2/dbhagat2.github.io/tree/main/python_notebooks/Assignment10.ipynb" text="The Analysis" %}
</div>

