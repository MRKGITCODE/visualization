# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    
Summary of the Dataset

Dataset Name: Fire Incidents
Source: Open Toronto - Fire Incidents

Description: The dataset includes detailed information on fire incidents as defined by the Ontario Fire Marshal (OFM) to which the Toronto Fire Service (TFS) responded. The data spans up to December 31, 2023. This dataset provides more granular details compared to the basic incidents dataset, with a format similar to the reporting data sent by TFS to the OFM. For privacy reasons, personal information is excluded, and exact addresses are aggregated to the nearest major or minor intersection. Some incidents are excluded pursuant to exemptions under Section 8 of the Municipal Freedom of Information and Protection of Privacy Act (MFIPPA).
Key Points:

Starting Date: Data collection started in 2011

Refresh Date: Last refreshed on July 30, 2024

Total Rows: 32,930

Total Columns: 43
Columns Used in Visualizations:

Area_of_Origin: OFM Area of Origin code and description.

Civilian_Casualties: Count of civilian casualties, including fire-related injuries or fatalities.

Estimated_Dollar_Loss: Estimated financial loss due to the fire.

Fire_Alarm_System_Operation: OFM Fire Alarm System Operation code and description.

Fire_Alarm_System_Presence: OFM Fire Alarm System Presence code and description.
Dataset Utility:

Public Safety: Helps analyze fire incidents to improve public safety measures.

Policy Making: Provides data for policymakers to make informed decisions about fire safety regulations.

Resource Allocation: Assists in allocating resources effectively for fire prevention and emergency response.

Research: Provides a rich dataset for academic and practical research in fire safety and urban planning.

By understanding the dataset and its structure, stakeholders can better utilize the information for improving fire safety protocols and emergency response strategies in Toronto.
Bar chat "Top 10 Most Frequent Areas of Origin for Fire Incidents"

> What software did you use to create your data visualization?
I used Plotly Express to create the data visualization.

> Who is your intended audience? 

The intended audience for this visualization includes fire safety officials, urban planners, policymakers, and the general public. This audience is interested in understanding the common areas where fire incidents originate to improve safety measures, allocate resources effectively, and raise public awareness.

> What information or message are you trying to convey with your visualization? 

The message of the visualization is to highlight the top 10 most frequent areas of origin for fire incidents responded to by the Toronto Fire Service (TFS) up to December 31, 2023. The aim is to inform stakeholders about the most common locations of fire incidents, the frequency of these incidents, the estimated dollar loss, and civilian casualties associated with them.

> What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 

The data presented is relevant and directly related to fire safety. It includes meaningful metrics such as the frequency of incidents, estimated dollar loss, and civilian casualties.

The plot uses a clean, white background with contrasting colors to enhance readability. Titles, labels, and annotations are clearly legible with an appropriate font size and style. The color palette 'Plasma' provides a visually appealing and distinguishable gradient.

> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

To ensure reproducibility, I used Python scripts with libraries such as Plotly, Pandas. These scripts can be shared and run in any Python environment with the necessary dependencies installed, ensuring that others can recreate the visualization with the same dataset.

> How did you ensure that your data visualization is accessible?  
To enhance accessibility, I:
- Used high-contrast colors for better visibility.
- Included descriptive labels and annotations to provide context.
- Ensured that the font size is large enough for easy reading.
- Provided interactive elements (hover data) that allow users to explore additional details without cluttering the main visualization.

> Who are the individuals and communities who might be impacted by your visualization?  

Residents of areas frequently affected by fires, as they may take preventive measures.
Fire safety officials and policymakers, who can use the information to implement targeted fire safety campaigns and allocate resources more effectively.
Urban planners and building inspectors, who can incorporate findings into building codes and safety regulations.

> How did you choose which features of your chosen dataset to include or exclude from your visualization? 

I included features that are most relevant to understanding the context and impact of fire incidents:
- Included: Area of Origin, Frequency, Estimated Dollar Loss, and Civilian Casualties. These metrics provide a comprehensive overview of the common areas of origin, their frequency, financial impact, and human toll.
- Excluded: Detailed temporal data, exact coordinates, and other less relevant attributes to maintain clarity and focus on the key message.

> What ‘underwater labour’ contributed to your final data visualization product?

Data Cleaning: Ensuring the dataset was free from missing or inconsistent values.
Preprocessing: Aggregating data to focus on the top 10 most frequent areas of origin.
Testing: Running multiple iterations of the visualization to ensure clarity, accuracy, and aesthetics.
Troubleshooting: Resolving issues related to software dependencies, exporting images, and ensuring interactive elements function as expected.
Documentation: Writing clear, reproducible code and annotations for others to understand and replicate the visualization process.

Heatmap: "Fire Incidents by Area of Origin and Fire Alarm System Presence"

 > What software did you use to create your data visualization?
 The heatmap was created using Tableau.
 
> Who is your intended audience? 

The intended audience includes fire safety analysts, building inspectors, and emergency response teams who need to analyze the relationship between fire incidents and the presence of fire alarm systems.

> What information or message are you trying to convey with your visualization? 

The heatmap illustrates the relationship between the area of origin for fire incidents and the presence or absence of fire alarm systems, highlighting areas with high civilian casualties.

> What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 

Substantive: Focused on the impact of fire alarm systems on fire incidents.
Perceptual: Used a color gradient to represent the number of civilian casualties, making it easy to identify high-risk areas.
Aesthetic: Ensured readability with clear labels, appropriate font sizes, and a contrasting color palette.

> How did you ensure that your data visualizations are reproducible? 
If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
The visualization was created using Tableau, which allows for reproducibility through saved workbooks and shared dashboards.

> How did you ensure that your data visualization is accessible?  

The heatmap uses high-contrast colors and readable fonts. The color palette was chosen to be colorblind-friendly, and the layout was designed to be easy to navigate.

> Who are the individuals and communities who might be impacted by your visualization?  

Fire safety officials, building inspectors, and local government authorities may use this visualization to identify areas that require improved fire alarm systems.

> How did you choose which features of your chosen dataset to include or exclude from your visualization? 

Focused on the areas of origin, the presence of fire alarm systems, and civilian casualties to provide a comprehensive view of the impact of fire alarm systems on fire incidents.

> What ‘underwater labour’ contributed to your final data visualization product?

Data cleaning and preprocessing steps were performed to ensure the dataset was accurate and suitable for visualization. Several iterations of adjusting the color palette and layout in Tableau were necessary to achieve the final result.




- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
