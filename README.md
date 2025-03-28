Dataset Description:

The dataset, titled CRM_Donor_Simulation_Dataset_With_Gender.csv, contains simulated CRM data for 5,000 donors. Each row represents an individual donor, including their personal and behavioral attributes. Key columns include DonorID, FirstName, LastName, Email, and Phone, providing basic identity and contact information. Location data is captured through City, State, and ZipCode. The LastDonationDate column records when the donor last gave, while TotalGifts and TotalAmountDonated offer insights into donation frequency and lifetime giving value. EventParticipation indicates how often the donor engaged with organizational events, and EngagementScore serves as a composite metric for overall involvement. A new Gender column was added to enable gender-based analytics, assigning each donor a randomly selected value of either "Male" or "Female" to support diversity insights.

Code & Notebook Description:

The notebook titled DonorIQ_CRM_Analytics_Updated.ipynb is a comprehensive exploratory data analysis (EDA) tool tailored for CRM donor data. It begins by loading and cleaning the dataset, followed by statistical overviews of key numerical features like total donations and engagement scores. The notebook performs segmentation to identify high-value donors, low-engagement individuals, and patterns in event participation. It includes data visualizations: such as histograms, pie charts, and scatter plots to make trends and outliers more intuitive. Since the original dataset lacked a Gender column, the notebook was updated to use the enhanced version of the dataset. This allows for deeper demographic analysis and helps nonprofits better understand donor diversity and behavior across gender lines.