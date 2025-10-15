# FIT3179 Data Visualisation 2 - Assignment Specification

## Assignment Overview

**Weight:** 25% of final unit mark  
**Due Date:** Sunday of Week 11, 15 October, 23:55  
**Submission:** PDF report via Turnitin on Moodle  
**Interview Hurdle:** Week 12 studio sessions (mandatory - zero mark if failed)

---

## Core Objective

Design and build an effective data visualization for a specific domain using the Vega-Lite visualization library to create maps and diagrams.

---

## Key Requirements

### 1. Domain Selection

- Choose a domain **distinct from your Data Visualisation 1 assignment**
- Address a specific need within the chosen domain
- Target audience: Average Australian or Malaysian audience
- Transform data into meaningful insights that are otherwise challenging to obtain

### 2. Technical Requirements

#### Vega-Lite Library

- Primary tool for creating maps and diagrams
- If other libraries are necessary for specific diagrams not feasible with Vega-Lite, obtain **prior approval from your tutor**

#### Web Page Creation

- Develop a **publicly accessible web page** hosted on your GitHub account
- JSON descriptions of each Vega-Lite diagram/map must be:
  - Easily accessible in the same repository
  - Human-readable

#### Performance Considerations

- Vega-Lite visualizations must load **efficiently**
- Total downloadable size: **< 1 megabyte**
- If larger size needed (videos, large images), discuss with tutor before submission

#### Geographic Map Requirement

- Web page **must include at least one geographic map**
- If map not pertinent to domain, seek exemption from tutor

### 3. Design & Interactivity

#### Interactivity

- Provide interactive exploration features
- Enable users to engage with and explore the data dynamically

#### Innovation

- Demonstrate innovation through:
  - Unique visualization methods, OR
  - Novel exploration of an interesting dataset

#### Design Methodologies

- **Five Design Sheet (FDS) methodology** for sketching and planning
- **Munzner What/Why/How framework** to assess:
  - Data types
  - Visualization goals
  - Design choices

#### Design Principles

Apply the following principles:

- Data-ink ratio
- Storytelling
- Layout
- Typography
- Appropriate use of visualization idioms with suitable marks and channels

---

## Task Schedule

### By End of Week 8

1. Select a domain for exploration
2. Identify relevant **publicly available datasets**
3. Discuss with tutor:
   - Your domain
   - Design ideas
   - Datasets
4. Design visualization using **Five Design Sheet methodology**

### Weeks 9 to 11

#### Weeks 9-10 Homework

- Create a map and a diagram with Vega-Lite
- If including these in final assignment, ensure they are **significantly improved versions**

#### Development Tasks

- Develop web page embedding Vega-Lite diagrams and maps
- Use CSS for typography and layout
- Make visualization publicly viewable as a **GitHub Page**

---

## Report Requirements

### Format

- **Maximum 1000 words** (excluding cover sheet and bibliography)
- Submit as PDF through Turnitin

### Required Sections

#### 1. Title Page

- Word count
- **URL of your visualization**

#### 2. Domain Description

- Brief description of the domain
- Purpose of the visualization
- Target audience

#### 3. Data Sources

- Details about data sources
- Authors of the data
- Relevance to the domain
- Data creation/collection process

#### 4. Visualization Rationale

- Rationale for chosen visualization methods
- Explanation of how visualizations assist users in achieving their tasks
- Justification for design choices

#### 5. Special Features (if applicable)

- Description of any custom-built elements
- Novel features or techniques used

---

## Submission Details

### What to Submit

1. **PDF Report** via Turnitin on Moodle
2. **Cover page** must include:
   - URL to public GitHub repository
   - Repository must contain web page with visualization

### Late Penalty

- **10% per day** penalty
- **One-week cut-off** (no submissions accepted after)

### Interview Hurdle

- Mandatory interview during Week 12 studio sessions
- **Failing this interview = zero mark for assignment**
- Be prepared to explain and defend your design choices

---

## Assessment Criteria

Your visualization will be assessed on:

1. **Domain Appropriateness** - How well the visualization addresses domain-specific needs
2. **Technical Implementation** - Effective use of Vega-Lite, performance, and code quality
3. **Design Quality** - Application of design principles and methodologies
4. **Interactivity** - Quality and usefulness of interactive features
5. **Innovation** - Unique approaches or novel insights
6. **Data Quality** - Appropriate selection and use of publicly available data
7. **Report Quality** - Clarity, conciseness, and completeness of written report
8. **Presentation** - Quality of the public GitHub page and overall presentation

---

## Checklist

### Before Week 8 Ends

- [ ] Domain selected (different from DV1)
- [ ] Publicly available datasets identified
- [ ] Initial discussion with tutor completed
- [ ] Five Design Sheet sketches completed

### Weeks 9-10

- [ ] Map created with Vega-Lite (homework)
- [ ] Diagram created with Vega-Lite (homework)
- [ ] Improvements planned for final versions

### Week 11

- [ ] Web page developed with embedded visualizations
- [ ] CSS styling applied (typography & layout)
- [ ] GitHub Page is public and accessible
- [ ] All JSON files are human-readable and accessible
- [ ] Performance optimized (< 1MB total size)
- [ ] At least one geographic map included
- [ ] Interactive features implemented
- [ ] Report written (max 1000 words)
- [ ] Report includes all required sections
- [ ] Cover page has visualization URL
- [ ] PDF submitted via Turnitin before 23:55 Sunday

### Week 12

- [ ] Prepared for interview hurdle
- [ ] Can explain design choices
- [ ] Can demonstrate visualization features
- [ ] Can discuss data sources and methodology

---

## Tips for Success

1. **Start Early** - Don't wait until Week 11 to begin
2. **Engage with Tutor** - Regular feedback helps improve your work
3. **Test Performance** - Ensure visualizations load quickly
4. **Document as You Go** - Makes report writing easier
5. **Practice Your Presentation** - Interview hurdle is crucial
6. **Choose Interesting Data** - Makes the project more engaging
7. **Focus on User Value** - Visualizations should provide real insights
8. **Iterate on Design** - Use FDS methodology to refine your approach

---

## Common Pitfalls to Avoid

1. ❌ Using the same domain as DV1
2. ❌ Exceeding 1MB download size without approval
3. ❌ Not including a geographic map (without exemption)
4. ❌ Using libraries other than Vega-Lite without approval
5. ❌ Making JSON files unreadable or inaccessible
6. ❌ Exceeding 1000-word limit in report
7. ❌ Forgetting to include visualization URL on cover page
8. ❌ Not preparing for the interview hurdle
9. ❌ Poor performance/loading times
10. ❌ Lack of interactivity or innovation

---

## Analysis of Current Project

### Current Status

Based on your existing `world_population_embedded.html` file:

#### ✅ Strengths

- **Embedded data approach** - Good for performance (no external file loading)
- **Vega-Lite usage** - Correct visualization library
- **Population data** - Relevant and interesting dataset
- **Geographic focus** - Appears to be map-based (ISO codes present)

#### 🔄 Areas to Consider

1. **Domain Selection**

   - Is world population different from your DV1 assignment?
   - What specific insights are you providing?
   - Who is your specific target audience?

2. **Interactivity**

   - Need to add interactive features (tooltips, filters, zooming, etc.)
   - Consider multiple coordinated views

3. **Multiple Visualizations**

   - Assignment requires both maps AND diagrams
   - Consider adding: bar charts, line graphs, scatter plots, etc.
   - Show different perspectives of population data

4. **Design Principles**

   - Apply FDS methodology
   - Document your design decisions
   - Ensure good typography and layout with CSS

5. **Data Sources**

   - Document where population data came from
   - Ensure it's publicly available
   - Consider using multiple related datasets

6. **GitHub Page**
   - Ensure it's publicly accessible
   - JSON should be human-readable
   - Consider code organization

### Recommended Next Steps

1. **Finalize Domain & Purpose**

   - Define specific research questions
   - Identify your target audience's needs
   - Clarify what insights you're providing

2. **Expand Visualizations**

   - Add at least one more diagram type
   - Ensure they work together to tell a story

3. **Add Interactivity**

   - Implement tooltips
   - Add filtering/selection capabilities
   - Consider linked brushing between views

4. **Improve Design**

   - Complete FDS sketches
   - Apply Munzner framework
   - Enhance CSS styling

5. **Prepare Documentation**

   - Start drafting report sections
   - Document data sources
   - Explain design rationale

6. **Optimize Performance**

   - Check total page size
   - Optimize data if needed
   - Test loading times

7. **Plan for Interview**
   - Practice explaining your choices
   - Be ready to discuss alternatives
   - Understand your code thoroughly
