# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
    
    Good Visualization: Line Chart (Time-Series Trend)

Example: Line Chart – https://datavizproject.com/data-type/line-chart

Reasons:

1. Perceptual Quality
Effectively uses position along a common scale (y-axis) and horizontal time progression (x-axis), which research by Cleveland & McGill (1984) identifies as one of the most accurate visual encodings for quantitative comparison. Viewers can easily detect trends, peaks, and declines because humans are highly sensitive to changes in slope and direction.
2. Substantive Quality
Accurately represents continuous data over time without distorting magnitude. When axes begin at logical baselines and intervals are evenly spaced, the chart honestly communicates rate of change, seasonality, and long-term patterns. It supports analytical tasks such as identifying growth trends or sudden shifts.
3. Aesthetic Quality
Clean layout with limited colors and minimal gridlines enhances readability. When designed well, line charts balance simplicity with clarity, allowing the viewer to focus on the narrative of change rather than decorative elements.

Improvements:

1. Add subtle annotations (e.g., markers for key events) to provide context without clutter.
2. Ensure color contrast is sufficient for accessibility and use distinct line styles (dashed/solid) for viewers with color vision deficiencies.

Bad Visualization: Radar (Spider) Chart

Example: Radar Chart – https://datavizproject.com/data-type/radar-chart

Reasons:

1. Perceptual Quality
Radar charts rely on angle and area comparison, which are perceptually weak encodings. It is difficult for viewers to accurately compare values across axes because there is no shared linear baseline. Small differences can appear exaggerated depending on axis scaling.
2. Substantive Quality
When multiple variables are plotted, overlapping shapes can obscure data and make interpretation confusing. Differences between categories may look dramatic due to the polygon shape rather than actual numeric variation, which risks misleading interpretation.
3. Aesthetic Quality
While visually striking, radar charts often become cluttered when multiple categories are displayed. The radial layout can overwhelm viewers, especially when labels are small or densely packed.

Improvements:

1. Replace with a grouped bar chart or parallel coordinates plot to improve comparability using aligned scales.
2. Limit the number of variables and clearly label each axis with consistent scaling to reduce distortion.    


- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 02/16/2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
