# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > **What software did you use to create your data visualization?**
        > I used Python (Matplotlib and Pandas) to generate the first set of visualizations. Python was chosen for its precision, transparency, and full reproducibility. I used Google Sheets for the second visualization, as it is accessible and well-suited for creating clean, comparative charts from tabular data.


    > **Who is your intended audience?** 
        > I assumed my main stakeholders were a group of greenhouse owners of Ontario concerned about rising costs and higher payrolls. The visualizations are designed for static use, either printed or presented in slides.
        >     
        > Other potential audiences include: 
        >   - Policymakers and agricultural economists evaluating cost trends.
        >   - Greenhouse operators making financial or operational decisions.
        >   - Academics and students studying agricultural sustainability in Ontario.
        >   - Journalists or members of the public interested in local food production.

    > **What information or message are you trying to convey with your visualization?** 
        > The first Python visualization is a side-by-side plot of major operational costs in Ontario’s greenhouse industry from 2014 to 2024. It highlights the evolution of payroll, purchase inputs, fuel, and electricity, showing an upward trend in all but fuel. The second subplot summarizes total sales versus total main operational costs. The main insight is that since 2022, and for the first time in many years (except for 2020), total sales have more than doubled total main operational costs, despite of its upward tendency since 2020. This suggests improved returns on operational investments.
        >     
        > It is important to note that the source doesn't mention other operational costs. Therefore, I assumed the selected categories represent the main sources of operational expenses. Also, due to the absence of data on machinery and installation acquisition or maintenance - for example - we cannot make conclusions about net gains.
        >     
        > The Google Sheets visualization compares the average payroll per employee in Ontario vs Canada between 2014 and 2023 (2024 data was not available). Ontario's payroll costs are rising and consistently outpacing the national average by approximately 13% to 16%.


    > **What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?**
        > For the Python visualizations, I considered:
        >   - Telling a short story addressing the main concern of the stakeholders.
        >   - Using colourblind safe colour scheme (e.g., #0072B2, #E69F00).
        >   - Including distinct marker shapes to aid users with low vision.
        >   - Adding grid lines and large fonts to enhance clarity.
        >   - Choosing a monospaced, accessible font (Arial) for better readability.
        >   - Applying whitespace thoughtfully to avoid visual clutter.
        > 
        > For the Google Sheets visualization, I used:
        >   - Side-by-side bar charts to display provincial vs national trends.
        >   - Percentage difference overlays to highlight the scale of divergence.
        >   - A consistent colour scheme and large, readable labels and fonts for accesibility.
    

    > **How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?** 
        > The Python plots are fully reproducible using the shared code and datasets. Anyone with access to the files can replicate the exact results.
        > 
        > Google Sheets is less reproducible due to manual formatting and chart building. This may reduce trustworthiness. However, I mitigated this by making the raw data and calculations accessible.
        > 
        > Raw data, basic calculations, and the Google Sheets visualization can be found under the Excel file named: *greenhouse1_en.xlsx*.


    > **How did you ensure that your data visualization is accessible?**  
        > Accessibility was addressed through:
        >   - High-contrast colours.
        >   - Text labels that do not rely on colour alone.
        >   - Sans-serif fonts in Google Sheets and monospaced fonts in Python.
        >   - Clean, uncluttered visuals.
        >   - Exporting static charts to ensure compatibility with screen readers.


    > **Who are the individuals and communities who might be impacted by your visualization?**  
        > This project is relevant to several groups:
        >   - Greenhouse workers and operators, whose livelihoods and strategies are influenced by the trends presented.
        >   - Policy stakeholders, who might use these data to adjust subsidies, energy regulation, or payroll policies.
        >   - Local food advocates, as rising costs could influence prices or production strategies.
        >   - Taxpayers and citizens, who benefit from a sustainable, affordable agricultural sector.


    > **How did you choose which features of your chosen dataset to include or exclude from your visualization?** 
        > For the Python visualizations, I selected the four core cost categories included in the raw data (payroll, fuel, electricity, and purchases) and summarized them against total cost and sales, I previously transformed the data to a "per '000 sqm" basis to allow comparison over time. More granular sales data, type of greenhouse, and total number of employees were excluded to reduce noise. Total area is implicitily used as the metrics are per '000 sqm.
        > 
        > In the Google Sheets visualization, I included provincial and national payroll data to offer comparative insight. The average payroll per employee was calculated.


    > **What ‘underwater labour’ contributed to your final data visualization product?**
        > A significant portion of this project involved unseen work and support:
        >   - Data sourcing, cleaning, and validation by researchers and assistants.
        >   - Designers behind accessible colour schemes.
        >   - IT support staff ensuring technical tools functioned smoothly.
        >   - Among many others...


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
* Submission Due Date: `23:59 - 11/02/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
