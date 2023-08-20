# Credit Union Balanced Scorecard
## Creating metrics and a balanced scorecard using NCUA call report data
These code files create metrics along with a balanced scorecard based on parameters set such as asset size.
Some important notes:
* I used just four easy to calculate metrics that don't fully represent a credit union's performance
* Metrics used should align with and support the strategy and goals of the organization
* The process to determine metrics and metric weights should be an iterative process involving various departments
* Credit unions vary in member bases, target markets, local economies, missions, and strategies and therefore it makes sense to carefully select a group of peers

Using a balanced scorecard can be a useful management tool to help identify strengths and improvement opportunities. 

## Basic code file description:
* **call_report_scorecard_data**: pulls data from ncua.gov and selects targeted fields for use in your scorecard file.
* **callreport_scorecard**: uses the csv output from the call_report_scorecard_data code, adds new fields focused on creating scorecard metrics, score the scorecard metrics on a 1-5 scale, creates an overall weighted score, and charts the results. 
