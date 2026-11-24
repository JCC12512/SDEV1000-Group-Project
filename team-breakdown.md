# SDEV1000 Project Team Breakdown

**Project:** Online Store Inventory Management System  
**Team size:** 4 students  
**Presentation length:** 5–10 minutes  

This plan divides the assignment so that every team member owns a complete section of the project. Each member is responsible for preparing, explaining, and presenting their assigned work.

---

## Member 1 - Inventory Structure and CRUD Operations

### Primary responsibility

Complete the Inventory Management Module overview and the product add, update, and remove operations.

### Assignment responsibilities

- Write the problem analysis and decomposition for the Inventory Management Module.
- Explain how the module is used by employees.
- Describe validations required by the system:
  - Unique alphanumeric ProductID
  - Non-empty ProductName
  - Valid Category
  - Positive Price
  - Quantity that is zero or greater
- Document **Adding a New Product**:
  - Functionality
  - Pseudocode
- Document **Updating an Existing Product**:
  - Modifying price
  - Modifying quantity
  - Modifying category
  - Functionality
  - Pseudocode
- Document **Removing an Existing Product**:
  - Functionality
  - Pseudocode
- Create one complete flowchart showing the inventory module menu and repeated operations.
- Include appropriate validation and error handling in the flowchart and pseudocode.

### Presentation responsibility

- Explain the Inventory Management problem analysis.
- Explain the inventory module flowchart.
- Summarize the add, update, and remove pseudocode.
- Demonstrate the validation rules using an example from `sales_data.xlsx`.

---

## Member 2 - Inventory Search, Sort, and Algorithm Justification

### Primary responsibility

Complete the Inventory Module search and sort functionality and explain all required search and sort algorithms.

### Assignment responsibilities

#### Search functionality

- Write pseudocode for **ProductName** search using Binary Search.
- Write pseudocode for **Category** search using Linear Search.
- Write pseudocode for **ProductID** search using either Linear or Binary Search.
- Justify the selected ProductID search algorithm.
- Provide an example demonstrating that each search returns the correct result.

#### Sort functionality

- Write pseudocode for sorting by ProductName using Merge Sort.
- Write pseudocode for sorting by Category using Bubble Sort.
- Write pseudocode for sorting by Price using either Merge or Bubble Sort.
- Justify the selected Price sort algorithm.
- Provide an example or test data for each sort.

#### Algorithm implementation and justification

- Explain Linear Search and its time complexity.
- Explain Binary Search and its time complexity.
- Explain Bubble Sort and its time complexity.
- Explain Merge Sort and its time complexity.
- Compare the benefits and drawbacks of each algorithm.
- Explain why the selected algorithms suit the inventory system.

### Presentation responsibility

- Present the inventory search and sort pseudocode.
- Explain the chosen search and sorting algorithms.
- Compare algorithm complexity and suitability.
- Demonstrate at least one search and one sort using example data.

---

## Member 3 - Sales Processing and Statistical Analysis

### Primary responsibility

Complete the Sales Processing Module and Statistical Analysis section.

### Assignment responsibilities

#### Sales Processing Module

- Write the Sales Processing problem analysis and decomposition.
- Describe the purchase process in complete sentences.
- Create a complete sales-process flowchart.
- Write pseudocode for:
  - Accepting ProductIDs and quantities
  - Finding the selected product
  - Checking available stock
  - Displaying insufficient-stock messages
  - Adjusting inventory quantities
  - Prompting the customer to continue or proceed to payment
- Calculate the 5% discount for individual products:
  - A 5% discount applies when quantity purchased is 8 or more.
  - The discount applies only to that product's subtotal.
- Write pseudocode for receipt generation.
- Show the purchased ProductNames, quantities, unit prices, line totals, discounts, and final total.

#### Statistical Analysis

- Write pseudocode to calculate **Total Revenue** for any input.
- Calculate the total revenue from `sales_data.xlsx`.
- Write pseudocode to calculate **Average Transaction Value** for any input.
- Calculate the average value of transactions across all unique OrderIDs.
- Explain how the calculations are performed.

### Presentation responsibility

- Present the sales process problem analysis and flowchart.
- Explain stock adjustment and insufficient-stock handling.
- Demonstrate a 5% discount calculation.
- Explain the total revenue and average transaction calculations.
- Show the total revenue and average transaction values.

---

## Member 4 - Reporting, Optimizations, and Final Assembly

### Primary responsibility

Complete the remaining reporting requirements and prepare the submitted document and presentation file.

### Assignment responsibilities

#### Product Analysis

- Write pseudocode to find the top five products by total quantity sold.
- Write pseudocode to find the bottom five products by total quantity sold.
- Identify the top five and bottom five products in `sales_data.xlsx`.
- Present the result using a labelled list and a bar chart.

#### Correlation Analysis

- Calculate the correlation between product Price and Quantity sold.
- Describe how the correlation coefficient was calculated.
- Interpret whether the relationship is positive, negative, or weak.
- Include a scatter plot or other appropriate visual representation.

#### Probability Analysis

- Calculate the probability of each product being sold on a given day.
- Include all dates in the full dataset date range.
- Include dates with no sales, even when they are missing from the CSV.
- Explain the probability formula and include a table or chart.

#### Trend Analysis

- Identify sales peaks and declines by date.
- Group sales quantity by category.
- Identify the best-performing categories.
- Include line, bar, or pie charts where appropriate.
- Compare findings across categories or time periods.

#### Optimizations

- Suggest at least two improvements that would increase system efficiency.
- Explain the benefit and any possible trade-off of each optimization.
- If an optimization is already incorporated into the design, explain why it is optimal.

#### Final assembly

- Combine all team sections into `project-submission.docx`.
- Check formatting and numbering.
- Verify that pseudocode, flowcharts, calculations, and screenshots are complete.
- Build one single presentation file containing all required presentation sections.
- Perform a final compliance review against the LMS rubric.

### Presentation responsibility

- Present the product analysis and visual comparisons.
- Present correlation and probability calculations.
- Present date and category trend findings.
- Explain at least two system optimizations.
- Coordinate the presentation sequence and ensure the deck is submitted as one file.

---

## Responsibility Distribution

| Team Member | Primary Content | Supporting Deliverables |
|---|---|---|
| Member 1 | Inventory overview and CRUD operations | 3 pseudocode sections, complete inventory flowchart |
| Member 2 | Inventory search and sort | 6 pseudocode operations, algorithm explanations and complexity |
| Member 3 | Sales processing | Complete sales flowchart, sales pseudocode, statistical analysis |
| Member 4 | Reporting and optimizations | Product, correlation, probability, trend findings, final assembly |

The original 36-mark Inventory Module is divided between Members 1 and 2.

The 20-mark Sales Processing Module is primarily owned by Member 3.

The 20-mark Reporting Module is primarily owned by Members 3 and 4:

- Member 3 owns Statistical Analysis.
- Member 4 owns Product, Correlation, Probability, and Trend Analysis.

The 12-mark Algorithm Implementation section is primarily owned by Member 2.

The 12-mark presentation is supported by all four members, with Member 4 responsible for final assembly.

---

## Shared Team Requirements

- Use `sales_data.xlsx` as the source data.
- Use consistent pseudocode formatting and variable names.
- Include units and labels in every numerical result.
- Use complete sentences for problem analysis and explanations.
- Clearly label all Excel tables and charts.
- Verify that all ProductIDs, prices, quantities, and discounts are interpreted correctly.
- Keep a shared checklist so that no required rubric item is missed.
- Review work with teammates before the final merge:
  - Member 1 reviews inventory terminology.
  - Member 2 reviews algorithm correctness.
  - Member 3 reviews sales discounts and statistics.
  - Member 4 reviews reporting calculations and final formatting.

---

## Presentation Sequence

Target a total presentation length of **5–10 minutes**:

1. **Member 1 - Inventory analysis and CRUD:** approximately 90–120 seconds
2. **Member 2 - Search, sort, and algorithms:** approximately 90–120 seconds
3. **Member 3 - Sales processing and statistical analysis:** approximately 90–120 seconds
4. **Member 4 - Product, correlation, probability, trend, and optimization findings:** approximately 120–150 seconds

Every member should:

- Present their assigned work directly.
- Explain one calculation or decision.
- Show one relevant chart, flowchart, pseudocode section, or example.
- Be prepared to answer a short question about their section.