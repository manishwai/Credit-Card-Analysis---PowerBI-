# **Credit Card Launch: Insights for Mitron Bank** ![Icon](https://img.icons8.com/ios-filled/50/000000/credit-card.png)

## **Project Overview**

Mitron Bank, a well-established financial institution headquartered in Hyderabad, is exploring the introduction of a new line of credit cards to broaden its product range and market presence. AtliQ Data Services has been engaged to conduct a pilot project using a sample dataset of 4,000 customers from five cities. The goal is to deliver a thorough analysis to support Mitron Bank's product strategy team.

## **Data Overview**

The analysis is based on the following two CSV files:

### **1. dim_customers**
- **customer_id**: Unique identifier for each customer.
- **gender**: Gender of the customer (Male, Female).
- **age_group**: Age category (21-24, 25-34, 35-45, 45+).
- **marital_status**: Marital status (Single, Married).
- **city**: City of residence (Mumbai, Delhi-NCR, Chennai, Hyderabad, Bengaluru).
- **occupation**: Occupation (Salaried IT Employees, Salaried Other Employees, Business Owners, Freelancers, Government Employees).
- **average_income**: Monthly average income in INR.

### **2. fact_spends**
- **customer_id**: Unique identifier for each customer, linking to dim_customers.
- **month**: Month of spending (May, June, July, August, September, October).
- **category**: Spending category (Entertainment, Apparel, Electronics, etc.).
- **payment_type**: Payment method (Debit Card, Credit Card, UPI, Net Banking).
- **spends**: Total amount spent by the customer in the specified month, category, and payment type.

## **Task Objectives**

### **Prepare an Interactive Dashboard**

- **Develop an interactive and self-explanatory dashboard** to cover the following analyses:

1. **Demographic Classification**
   - **Age Group Analysis**: Identify age groups more likely to use credit cards.
   - **Gender Insights**: Analyze if gender influences spending behavior.
   - **Occupation Trends**: Examine how different occupations impact spending patterns.

2. **Average Income Utilization Percentage**
   - **Calculate the average income utilization percentage** (`avg_spends / avg_income`) for each customer.
   - **Identify high-income utilizers** who are more likely to use credit cards.

3. **Spending Insights**
   - **Analyze spending patterns across various categories**.
   - **Assess the impact of factors** such as occupation, gender, city, and age on spending behavior.

4. **Key Customer Segments**
   - **Identify and profile key customer segments** likely to be high-value users of the new credit cards.
   - **Understand their demographics, spending behaviors, and financial preferences**.
   - **Category Analysis**: Determine which spending categories have the highest expenditure.
   - **Impact Factors**: Evaluate how age, city, and occupation affect spending in different categories.

5. **Credit Card Feature Recommendations**
   - **Provide recommendations on key features** for the new credit card.
   - **Features**: Suggest features that cater to identified customer needs and preferences.
   - **Incentives**: Recommend incentives or benefits to enhance credit card adoption.

## **Next Steps**

1. **Develop the Interactive Dashboard**: Create a dashboard to visualize and explore insights.
2. **Perform Detailed Analysis**: Conduct a deeper analysis based on dashboard findings.
3. **Prepare a Comprehensive Report**: Summarize insights and recommendations for the product strategy team.


###  Demographic Analysis Report


![App Screenshot](https://i.imgur.com/dX04VmT.png)
## 1. Total Customers

- **Total Number of Customers:** 4,000

## 2. Gender Distribution

- **Male Customers:** 2,597 (64.93%)
- **Female Customers:** 1,403 (35.08%)

## 3. Marital Status

- **Married Customers:** 3,136 (78.41%)
- **Unmarried Customers:** 864 (21.60%)

## 4. Age Group Distribution

- **25-35 Years:** 1,498 
  - **Males:** 966 
  - **Females:** 532
- **35-45 Years:** 1,273 
  - **Males:** 834 
  - **Females:** 439
- **45+ Years:** 538

## 5. City Distribution

- **Mumbai:** 1,078 
  - **Males:** 693 
  - **Females:** 385
- **Chennai:** 834
- **Bangalore:** 751
- **Delhi NCR:** 744
- **Hyderabad:** 593

## 6. Occupation Distribution

- **Salaried IT Employees:** 1,294 
  - **Males:** 721 
  - **Females:** 573
- **Salaried Other Employees:** 893
- **Freelancers:** 784
- **Business Owners:** 630
- **Government Employees:** 399

### . Customer Spending Analysis
![App Screenshot](https://i.imgur.com/bmJ1x4U.png)
### Total Spend by Gender

- **Male Spending:** 67.2%

### Total Spend by Occupation

- **Salaried IT Employees:** Key focus area due to high spending
- **Business Owners and Salaried Other Employees:** Notable spending categories

### Total Spend and Income Utilization by City

- **Mumbai:** Highest spend with a utilization rate of 51.43%
- **Delhi NCR:** Second highest spending city with a utilization rate of 48.03%

### Total Spend by Category

- **Bills:** 105M (Highest spending category)
- **Grocery:** 86M
- **Electronics:** 80M
- **Others:** 16M

### Average Monthly Income and Spending by Age Group

- **Age Groups 25-35 and 35-45:** Highest income utilization

### Average Monthly Income and Spending by Marital Status

- **Single Customers:** Higher average spending compared to married customers

### Payment Mode Analysis
![App Screenshot](https://i.imgur.com/iERlaiJ.png)
### Total Spending by Payment Mode

- **Credit Cards:** 216M (17.45% utilization rate)
- **UPI:** Increasingly popular, posing competition to credit cards

### Income Utilization by Occupation and Payment Mode

- **Salaried IT Employees and Salaried Other Employees:** Predominantly use Credit Cards, with UPI as a secondary option

### Income Utilization by Category and Payment Mode

- **Bills Category:** Mainly paid using Credit Cards
- **Groceries:** Preferred UPI due to ease of use

### Credit Card Usage by City and Age Group
![App Screenshot](https://i.imgur.com/ZLXKone.png)
- **Major Usage Cities:** Chennai, Delhi/NCR
- **Age Group:** 25-34 years primarily use Credit Cards across most categories, except for food and grocery shopping

## 9. Insights & Recommendations

### Age Group Insights & Recommendations
![image](https://github.com/user-attachments/assets/1815e185-854a-457d-a25f-42530054d1a0)

- Focus on age groups 25-35 and 35-45 for targeted marketing efforts.

### Spending Category Insights & Recommendations
![image](https://github.com/user-attachments/assets/9383f6a8-29d4-42cc-a010-958ea04def48)

- Emphasize marketing strategies on categories with the highest spending, such as Bills and Grocery.

### Occupation Insights & Recommendations
![image](https://github.com/user-attachments/assets/1ecbfb74-87f0-4e28-8f1b-e447c9c7f3eb)

- Prioritize engagement with Salaried IT Employees, Business Owners, and Salaried Other Employees due to their high spending levels.













