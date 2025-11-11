Proposal
================

## Team Member:

Eric Xu <sx2402@cumc.columbia.edu>  
Alexandria Taylor <at3583@cumc.columbia.edu>  
Kevin Guzman <kg3006@cumc.columbia.edu>  
Edmund Wong <ecw2178@cumc.columbia.edu>  
Jiseung Lee <jl6458@cumc.columbia.edu>

## Proposal(draft):

*This project aims to investigate survival outcomes in a pressing
women’s health issue, emphasizing the demographic and biological factors
that shape disease prognosis and health equity.*

**Primary Topic: Breast Cancer Survival and Risk Patterns**  
Breast cancer remains one of the most prevalent disease worldwide,
accounting for a substantial proportion of cancer incidence and health
burden. Despite advances in early detection and treatment, disparities
in outcomes is often suggested across demographic and biological groups.
Clinical outcomes are influenced by multiple factors, including tumor
size, stage, lymph node involvement, and hormone recpeotor status.

Understanding how patient characteristics, tumor biology, and receptor
profiles influence survival and risk is essential for improving risk
stratification and guide treatment decisions. This project aims to
explore the relationship between factors predicting surivial outcome
amoung patients who have breast cancer.

*This project starts with a public, de-identified dataset derived from
the 2017 SEER (Surveillance, Epidemiology, and End Results) Program,
containing information from 4,024 breast cancer cases with 16
demographic, clinical, and molecular variables. The data include
survival time, tumor stage and grade, hormone receptor status, lymph
node involvement, and other key prognostic factors.*

In further investigation, usage of this dataset or a full SEER dataset
with more detailed covariates would be considered. The main goal is to
explore survival differences by demographic group, tumor
characteristics, and receptor status, as well as broader examination of
disease burden and disparities in breast cancer outcomes.

The project may also incorporate publicly available SEER incidence data
(1975–2022) to contextualize survival findings within trends in breast
cancer occurrence and population-level risk patterns over time.

*If SEER data set is not applicable or not informative, an alternative
plan would be applied.*

**Alternative Topic: Infant and Maternal Mortality in the United
States**  
As an alternative or complementary direction, this project may
investigate patterns and disparities in infant and maternal mortality
using national data from the CDC/NCHS Birth–Infant Death and Maternal
Mortality datasets. These datasets provide detailed demographic and
health information on mothers and infants across the United States,
offering a rich foundation for understanding the social, economic, and
medical determinants of survival in early life and maternal health.

This topic is of major public health importance, as both infant and
maternal mortality reflect the overall effectiveness of healthcare
systems, access to care, and equity in health outcomes. Analyses could
focus on identifying demographic patterns, geographic disparities, and
population subgroups at elevated risk, contributing to ongoing national
efforts to reduce preventable deaths and improve maternal–child health
outcomes.

**Project Vision**

Both directions align closely with the goals of applied epidemiologic
and data science research. The overarching aim is to use population data
to describe health disparities across female health burden and
systematic determinants. With this project, we aim to identify key
determinants of disease outcomes, and highlight areas for intervention.
By integrating data management, exploratory insight, and public health
relevance, this project will contribute to understanding critical
patterns in population health and inform future work in epidemiology and
health equity.

## Final Product Plans

Our team will produc a fully reproducible, Github-hosted project that
identify predictors of surival in breast cancer. Deliverables will
inluce.

- **Final Writtent Report**: A comprehensive report detailing workflow
  following the required structure (Motivation, Related Work, Data,
  Exploratory Analysis, Additional Analysis, Disucssion).

- **Interactive Project Website**: Built uing R Markdown, hosted via
  GitHub Pages, and design to communicate reulsts to a broad audiance.

- **Tow-minute Video Summary**: A concise video presentation summarizing
  key findings, methodology, and public health implications of the
  project that is embedded into the project webpage.

- **GitHub Reprository**: A well-organized repository containing all
  code, data processing scripts, and documentation to ensure full
  reproducibility of the analysis.

## Planned Analysis/Visualization/Coding Challanges

### Planned Analysis:

- Descriptive statistic and distribution of demographics and clincial
  variables

- Correlation and association test between tumor characteristics/lymph
  node characteristics/hormone receptor status and survival outcomes

- Kaplan-Meier surivival analysis

- Cox proportional hazards regression

### Visualizations:

- Kaplan-Meier survival curves stratified by key variables (e.g., tumor
  stage, hormone receptor status)

- Boxplots of tumor size by stage

- Heatmap of variables correlation

### Coding Challenges:

- Data cleaning and preprocessing of SEER dataset (if able to be)

- Cleaning categorial variables in publicly available data set

- Reformating data for surival analysis

- Managing missing or inconcsistent data enteries.

## Project Timeline

<div id="dqdfsxegqh" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#dqdfsxegqh table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
&#10;#dqdfsxegqh thead, #dqdfsxegqh tbody, #dqdfsxegqh tfoot, #dqdfsxegqh tr, #dqdfsxegqh td, #dqdfsxegqh th {
  border-style: none;
}
&#10;#dqdfsxegqh p {
  margin: 0;
  padding: 0;
}
&#10;#dqdfsxegqh .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 14px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}
&#10;#dqdfsxegqh .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}
&#10;#dqdfsxegqh .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}
&#10;#dqdfsxegqh .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}
&#10;#dqdfsxegqh .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#dqdfsxegqh .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#dqdfsxegqh .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}
&#10;#dqdfsxegqh .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}
&#10;#dqdfsxegqh .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}
&#10;#dqdfsxegqh .gt_column_spanner_outer:first-child {
  padding-left: 0;
}
&#10;#dqdfsxegqh .gt_column_spanner_outer:last-child {
  padding-right: 0;
}
&#10;#dqdfsxegqh .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}
&#10;#dqdfsxegqh .gt_spanner_row {
  border-bottom-style: hidden;
}
&#10;#dqdfsxegqh .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}
&#10;#dqdfsxegqh .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}
&#10;#dqdfsxegqh .gt_from_md > :first-child {
  margin-top: 0;
}
&#10;#dqdfsxegqh .gt_from_md > :last-child {
  margin-bottom: 0;
}
&#10;#dqdfsxegqh .gt_row {
  padding-top: 6px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}
&#10;#dqdfsxegqh .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#dqdfsxegqh .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}
&#10;#dqdfsxegqh .gt_row_group_first td {
  border-top-width: 2px;
}
&#10;#dqdfsxegqh .gt_row_group_first th {
  border-top-width: 2px;
}
&#10;#dqdfsxegqh .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#dqdfsxegqh .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}
&#10;#dqdfsxegqh .gt_first_summary_row.thick {
  border-top-width: 2px;
}
&#10;#dqdfsxegqh .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#dqdfsxegqh .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#dqdfsxegqh .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}
&#10;#dqdfsxegqh .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}
&#10;#dqdfsxegqh .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}
&#10;#dqdfsxegqh .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}
&#10;#dqdfsxegqh .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#dqdfsxegqh .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#dqdfsxegqh .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}
&#10;#dqdfsxegqh .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}
&#10;#dqdfsxegqh .gt_left {
  text-align: left;
}
&#10;#dqdfsxegqh .gt_center {
  text-align: center;
}
&#10;#dqdfsxegqh .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}
&#10;#dqdfsxegqh .gt_font_normal {
  font-weight: normal;
}
&#10;#dqdfsxegqh .gt_font_bold {
  font-weight: bold;
}
&#10;#dqdfsxegqh .gt_font_italic {
  font-style: italic;
}
&#10;#dqdfsxegqh .gt_super {
  font-size: 65%;
}
&#10;#dqdfsxegqh .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}
&#10;#dqdfsxegqh .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}
&#10;#dqdfsxegqh .gt_indent_1 {
  text-indent: 5px;
}
&#10;#dqdfsxegqh .gt_indent_2 {
  text-indent: 10px;
}
&#10;#dqdfsxegqh .gt_indent_3 {
  text-indent: 15px;
}
&#10;#dqdfsxegqh .gt_indent_4 {
  text-indent: 20px;
}
&#10;#dqdfsxegqh .gt_indent_5 {
  text-indent: 25px;
}
&#10;#dqdfsxegqh .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}
&#10;#dqdfsxegqh div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>
<table class="gt_table" style="table-layout:fixed;width:0px;" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <colgroup>
    <col style="width:180px;"/>
    <col style="width:220px;"/>
    <col style="width:420px;"/>
  </colgroup>
  <thead>
    <tr class="gt_heading">
      <td colspan="3" class="gt_heading gt_title gt_font_normal gt_bottom_border" style><span class='gt_from_md'><strong>Project Timeline (4 Weeks)</strong></span></td>
    </tr>
    &#10;    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="Week-/-Date">Week / Date</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="Milestone">Milestone</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="Key-Tasks">Key Tasks</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="Week / Date" class="gt_row gt_left"><span class='gt_from_md'>Week 1 (Nov 11–17)</span></td>
<td headers="Milestone" class="gt_row gt_left"><span class='gt_from_md'>Data Cleaning &amp; Setup</span></td>
<td headers="Key Tasks" class="gt_row gt_left"><span class='gt_from_md'>Import data, recode variables, handle missing values, set up GitHub repo &amp; R/Quarto structure.</span></td></tr>
    <tr><td headers="Week / Date" class="gt_row gt_left"><span class='gt_from_md'>Week 2 (Nov 18–24)</span></td>
<td headers="Milestone" class="gt_row gt_left"><span class='gt_from_md'>Exploratory Analysis &amp; Visualization</span></td>
<td headers="Key Tasks" class="gt_row gt_left"><span class='gt_from_md'>Descriptives &amp; plots; correlations; refine questions; draft report sections.</span></td></tr>
    <tr><td headers="Week / Date" class="gt_row gt_left"><span class='gt_from_md'>Week 3 (Nov 25–Dec 1)</span></td>
<td headers="Milestone" class="gt_row gt_left"><span class='gt_from_md'>Modeling &amp; Interpretation</span></td>
<td headers="Key Tasks" class="gt_row gt_left"><span class='gt_from_md'>Kaplan–Meier &amp; Cox models; test associations; interpret results; finalize figures &amp; tables.</span></td></tr>
    <tr><td headers="Week / Date" class="gt_row gt_left"><span class='gt_from_md'>Week 4 (Dec 2–Dec 6)</span></td>
<td headers="Milestone" class="gt_row gt_left"><span class='gt_from_md'>Final Deliverables &amp; Submission</span></td>
<td headers="Key Tasks" class="gt_row gt_left"><span class='gt_from_md'>Finish report &amp; website; record 2-min screencast; polish repo; submit by Dec 6 (11:59 PM).</span></td></tr>
  </tbody>
  &#10;</table>
</div>
