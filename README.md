# 🎧 Airline Customer Support Operations Analysis

## 📌 Project Overview
This project analyzes customer support tickets for an airline to evaluate operational efficiency and service quality. By examining ticket lifecycles (from Open to Closed), issue types, and resolution costs, I identified bottlenecks in customer service and areas for cost optimization.

## 📌 Business Problem

Airlines struggle to efficiently manage customer support tickets, which affects customer satisfaction, operational efficiency, and overall cost management. Identifying bottlenecks and high-impact issues is critical to improving service quality and reducing operational expenses.

## 🔍 Key Business Questions Addressed:
1. **Efficiency:** What is the average resolution time (SLA) for different issue types?
2. **Cost Analysis:** Which countries or issue types incur the highest estimated costs?
3. **Volume & Channels:** Which channel (Email, Phone, etc.) is most used by customers?
4. **Prioritization:** Are high-priority tickets being resolved faster than low-priority ones?

## 🎯 Objective

Analyze airline customer support tickets to:

Identify patterns in issue types, departments, and channels
Measure resolution duration and estimated costs
Provide actionable recommendations to optimize operations and customer satisfaction.

## 📊 Dataset Columns Included:
* **Ticket Tracking:** Ticket ID, Status (Open/Closed), Priority.
* **Customer Info:** Name, Country, Contact Details.
* **Operational Metrics:** Issue Type, Channel (Source of complaint), Estimated Cost.
* **Timeline:** Date Opened, Date Closed (Duration Analysis).

## 💡 Key Insights
# 1. Ticket Volume & Customers
Total tickets analyzed: 10,000+
Total unique customers: 9404
Average resolution duration:21 days

High ticket volume months correspond to seasonal peaks, suggesting need for temporary staffing or proactive issue handling.

# 2. Channel Analysis
Customers primarily contact support via Channel Chat and Email (50%)
Other channels (In-Person, WhatsApp,Phone and other ) account for 50%

Recommendation: Invest in most-used channels to improve efficiency and response times.

# 3. Issue Type Distribution
Top 3 issues: Billing Error(15%),Refund Request(15%) and Late delivery with 14%

Recommendation: Focus process improvements on top recurring issue types to reduce total ticket load.

# 4. Department Workload
Department Finance handles 17% of total tickets
Department Logistics handles 17%
Department Sales handles 17%

Recommendation: Reallocate resources or provide additional training to high-load departments.

# 5. Ticket Status & Priority
Open tickets: 75%, Closed tickets: 25%
High priority issues take 22 days on average to resolve vs 22 or 20 days for medium/low

Recommendation: Prioritize high priority tickets to reduce resolution time and customer impact.

# 6. Country Analysis
Country Jordon has the highest number of issues (1708 tickets)
Country Lebanon follows with 1703 tickets

Recommendation: Investigate systemic issues in top countries and tailor support strategy accordingly.

# 7. Cost Analysis
Maximum estimated cost per issue type: $500
Maximum cost per country: $500

Recommendation: Address costly issue types first to optimize operational budget.

# 8. Trends Over Time
Peak months for ticket opening: Month August & October
Average resolution duration spikes in these months

Recommendation: Plan staffing and support resources based on historical peak periods.

## 🚀 Recommendations Summary
Prioritize high-priority tickets to reduce resolution time and improve satisfaction.
Focus on top recurring issue types and high-cost tickets to reduce operational burden.
Invest in most-used support channels for faster response and customer engagement.
Allocate resources to departments with highest ticket volume to balance workload.
Plan staffing around peak months to maintain service efficiency.

## 💰 Business Impact
- Faster resolution of high-priority tickets → reduces customer churn
- Addressing top recurring issues → lowers operational costs
- Optimizing channels and department workloads → improves service efficiency and satisfaction
- Proactive planning for peak months → enhances operational scalability
- Reducing resolution time can significantly improve customer satisfaction
- Identifying high-cost issues helps optimize operational expenses
- Improving response efficiency reduces customer complaints and churnز

## Notes
Some tickets showed extremely high resolution times (200+ days), which were treated as outliers and excluded using the average duartion which is 90 days 
as i have tried to use IQR bit lower and upper bound is very strange.

## 📊 Visualizations / Dashboard
<img width="292" height="143" alt="image" src="https://github.com/user-attachments/assets/be2fe2ae-5dae-4024-9d3d-f701f9d5e6b2" />

<img width="293" height="143" alt="image" src="https://github.com/user-attachments/assets/fbdd3276-b5c6-45e0-90aa-6f9efbb4c5c1" />

<img width="292" height="141" alt="image" src="https://github.com/user-attachments/assets/e7fd962e-1bbf-462d-8fd1-94513cc65e17" />

<img width="870" height="481" alt="image" src="https://github.com/user-attachments/assets/9487d662-e526-47a1-8ac3-6f75404cf935" />

We can find that 50% of customers use chats and emails to tell airport about their issues.

<img width="981" height="479" alt="image" src="https://github.com/user-attachments/assets/0e97718e-4060-45ab-b846-82f804f67e45" />

We can find 30% of issue is from billing error and refund request and 70% of other types.

<img width="899" height="452" alt="image" src="https://github.com/user-attachments/assets/2f9d03ac-8879-4b4d-9c51-02f53927f1f4" />

We can find that 17% of issues Finance department have to handle them with.

<img width="967" height="452" alt="image" src="https://github.com/user-attachments/assets/1607f5a1-abe0-4e50-9b9c-c729d09fbfc5" />

We can find 35% of issues comes from people who from Jordon and Lebanon

<img width="875" height="452" alt="image" src="https://github.com/user-attachments/assets/da4ab995-5c2d-421e-8143-ec7caf8bfff3" />

We can find that 34% of issues are from high priority

<img width="964" height="452" alt="image" src="https://github.com/user-attachments/assets/f54a1c0d-63d3-419a-8f55-516aebc4fbb5" />

We can find 75% of issues are still opened and we have to solve them as soon as possible 

<img width="843" height="513" alt="image" src="https://github.com/user-attachments/assets/1ca63579-3301-43d8-99d9-46d172650031" />

We can find that Billing error issue type is the most issue types with opened issues so we have to care about them  and it considers the issue type with highest number of closed issues  

<img width="977" height="532" alt="image" src="https://github.com/user-attachments/assets/ffd652e2-1fb5-411f-af34-029d240ba469" />

We can find August is month with the highest number of opened issues 673 issues so we have to care about it and try to reduce number of opened issues

<img width="831" height="452" alt="image" src="https://github.com/user-attachments/assets/b3c242d0-9691-4088-acee-79d99fb0f4de" />

We can find that May is the month with the longest duration to solve issues with 39 days

<img width="962" height="452" alt="image" src="https://github.com/user-attachments/assets/8056b8f4-f990-47a6-bc21-177916f36f64" />

We can find most of departments takes max duration to solve issues 90 days 

<img width="822" height="560" alt="image" src="https://github.com/user-attachments/assets/7ea951a3-cba3-4897-b006-758e02af98a9" />

We can find that Billing Error issue the most common issue takes average 24 days to be solved

<img width="955" height="530" alt="image" src="https://github.com/user-attachments/assets/5ea43a01-faf5-490c-9937-580431fb3b6e" />

We can find High priority issues take 22 days on average to resolve vs 22 or 20 days for medium/low

<img width="828" height="477" alt="image" src="https://github.com/user-attachments/assets/486da1d1-3572-4076-8143-c5523da41dab" />

We can find that most of issues takes max estimated cost about 500 dollars

<img width="929" height="452" alt="image" src="https://github.com/user-attachments/assets/eda4f02f-525a-4e13-933a-31e336522436" />

We can find most of issues comes from people who is from UAE, EGYPT,JORDON,SAUDI ARABIA AND LEBANON are the most expensive issues based on cost

## 🛠️ Tools Used:
* **Microsoft Excel:** (Calculated Columns for "Time to Resolve", Pivot Tables, Data Cleaning).








