# Ecommerce optimisation

![Esta es una imagen](/Datos/Imagenes/featured.jpg)

- [Introduction](#introduction)
- [Objectives](#objectives)
- [Project results](#project-results)
    - [Insights (baseline)](#insights) 
    - [Actionable initiatives](#actionable-initiatives) 
- [Project structure](#project-structure)
- [Instructions](#instructions)

## Introduction <a name="introduction"></a>
The client is an ecommerce in the cosmetics sector that seeks to break the trend of null evolution obtained during the last months.

- [See a technical explanation of project here.](https://pedrocorma.github.io/project/3ecommerce/)

## Objectives <a name="objectives"></a>
1. Analysing the ecommerce transactional data to find potential conversion rate optimisation (CRO) actions that increase visits, conversions and the average ticket, and therefore increase overall ecommerce revenue.
2. Creating advanced analytical assets such as RFM segmentation and a recommendation system to drive goal achievement.

## Project results  <a name="project-results"></a>
### Insights (baseline)  <a name="insights"></a>
1. In each session, on average:
   - 2.2 products are viewed.
   - 1.3 items are added to cart.
   - 0.9 items were removed from your cart.
   - 0.3 products are purchased.
2. Cross-selling: average of 5 products per purchase.
3. Recurrence: 10% of customers return to purchase after the first month.
4. Conversion rates:
   - 60% of add to cart over views.
   - 22% of purchases over cart additions.
   - 13% of purchases over views.
5. Average monthly turnover: 125.000€.

### Actionable initiatives  <a name="actionable-initiatives"></a>
A plan of 10 specific initiatives organized into 5 major business levers has been derived from the exploratory data analysis to break the flat evolution of the company’s KPIs over the last few months and achieve an overall increase in ecommerce revenues:

**Actions to increase the number of views:**
1. Revise paid campaigns (generation and retargeting) to concentrate investment in time slots between 9am and 1pm and between 6pm and 8pm.
2. Concentrate investment in Christmas and post-Christmas campaigns in the week of black friday.
3. Increase investment to the maximum CPA based on the LTV identified.

**Actions to increase conversion rates:**
4. Preconfigure the home page with the products identified in the most viewed and most sold analysis.
5. Work on products with high cart abandonment rate.
6. Work on products that are highly viewed but rarely purchased and on products that are highly purchased but rarely viewed.

**Actions to increase cross-selling:**
7. The median purchase includes 5 products. Increase this ratio through real-time recommendation with the new recommender.

**Actions to increase purchase frequency:**
8. 90% of customers make only one purchase. Create a regular newsletter with the new recommendation system to increase visit frequency.
9. Conduct promotional campaigns on the top segments of the RFM segmentation.

**Customer loyalty actions:**
10. Create a loyalty program segmented by the new developed RFM segmentation.

## Project structure <a name="project-structure"></a>
- :file_folder: Datos
  - :file_folder: Imagenes:  Contains project images.
- :file_folder: Notebooks
  - `01_Diseño del proyecto.ipynb`: Notebook compiling the initial design of the project.
  - `02_Creacion del Datamart Analitico.ipynb`: Notebook creating analitic datamart (loading and unifying data, applying data quality processes, ...).
  - `03_Analisis e Insights.ipynb`: Notebook used for the execution of the exploratory data analysis and which collects the business insights found as well as the recommended actionable initiatives.
- 📈 Business_Case_.xlsx: Business Case excel file.

## Instructions  <a name="instructions"></a>
- Unzip ecommerce.rar and tablon_analitico.rar under 'Datos' folder.
- Remember to update the `project_path` to the path where you have replicated the project.
