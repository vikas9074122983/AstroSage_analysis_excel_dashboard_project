# AstroSage_analysis_excel_dashboard_project
data analysis project using excel and excel dashboard
AstroSage Call Center Performance Analysis & Investment Strategy
This repository contains a comprehensive analysis of the AstroSage call center's operational data. The project's goal is to identify key performance issues and provide data-driven recommendations for allocating a ₹1 crore investment to enhance operational efficiency, improve customer satisfaction, and boost profitability.


An interactive dashboard was created to visualize key performance indicators. 

📝 Problem Statement
AstroSage has received a ₹1 crore investment to optimize its call center operations. The primary challenge is to determine the most effective allocation of these funds across technology upgrades, agent training, and hiring to achieve the highest return on investment.

📊 The Dataset
The analysis is based on a single table with 35 attributes, capturing detailed information about customer-agent interactions. The dataset includes:



Interaction Details: User and Guru IDs, consultation type (Call, Chat), status (completed, failed, busy), and duration.




Financial Data: Net amount, astrologer earnings, and refund status.



Customer Feedback: User ratings for consultations.


Metadata: Timestamps, platform used (website, app), and other session identifiers.


⚙️ Methodology & Analytical Approach
The project followed a structured approach to transform raw data into actionable insights.

Data Cleaning & Preprocessing:

Handled missing and inconsistent values by filling blank cells with "N/A" for text and 0 for numerical data.

Normalized date/time columns to enable time-series analysis.

Exploratory Data Analysis (EDA):

Utilized Pivot Tables extensively to aggregate data and analyze key metrics like daily call volume, revenue by product, and agent performance.



Employed spreadsheet functions like AVERAGEIF, COUNTA, and CORREL to calculate KPIs and correlations.



Visualization:

Developed an interactive dashboard featuring various charts (Pie, Bar, Line) to provide a comprehensive view of call center performance.



Used slicers for dynamic filtering by month, country, and consultation type.


💡 Key Findings & Insights
The analysis uncovered several critical operational challenges and opportunities:

🚨 High System Failure Rate: A significant portion of interactions fail. 59% of calls don't complete successfully (failed, busy, no-answer, incomplete) , and 71% of chats are either failed or incomplete. This is the biggest point of customer frustration and lost revenue.



😞 Low Customer Satisfaction: The average Guru rating is very low at 2.93 out of 8. This is heavily skewed by a large number of '0' ratings, likely assigned automatically to failed interactions.



📞 Calls Drive Revenue: Calls are the most valuable channel, generating 79% of the total revenue compared to 21% from chat.


🕒 Peak Operational Hours: User volume peaks significantly between 6 AM and 5 PM, indicating a clear window where staffing and system stability are most crucial.


⚖️ Unbalanced Workload: The top 10 consultants handle 44% of the total call volume, suggesting an uneven distribution that could lead to agent burnout and inconsistent service quality.

🚀 Strategic Recommendations & Budget Allocation
Based on the findings, the ₹1 crore investment should be prioritized to fix foundational issues before scaling the team.

Investment Allocation: ₹1 Crore 

1. Technology Upgrade (60% - ₹60 Lakhs) 


Justification: The high failure rates for calls (59%) and chats (71%) are the root cause of poor customer satisfaction and lost revenue. Upgrading the core infrastructure is the top priority.


Action: Invest in a new cloud-based Omnichannel Contact Center platform with robust Automatic Call Distributor (ACD), callback features, and a reliable chat system.

2. Targeted Agent Training (25% - ₹25 Lakhs) 

Justification: A new system requires proficient users. Training is needed to improve service quality, handle interactions efficiently on the new platform, and leverage best practices from top-performing agents.


Action: Develop comprehensive training on the new technology and a separate module on "Quality & Efficiency" based on analysis of high-rated agents.

3. Strategic Hiring & Incentives (15% - ₹15 Lakhs) 


Justification: Hiring should be a secondary step, undertaken only after technology fixes can support a higher volume of successful connections.


Action: Allocate funds to hire a small number of agents to cover peak hours and introduce a performance incentive program to reward agents who achieve high customer satisfaction and efficiency scores.


🛠️ Tools Used
Microsoft Excel / Google Sheets: For data cleaning, analysis (Pivot Tables, formulas), and visualization.

Microsoft PowerPoint: For presenting the final findings and recommendations.
