# CLUSTERING REGENCIES IN EAST JAVA BASED ON SOCIAL INDICATOR


This project implements the Self Organizing Maps (SOM) algorithm in Python to analyze social indicator data from regencies in east java. The dataset includes multidimensional social indicator variables—Population, Life Expectancy, Human Life Span, Average Years of Schooling, Birth Rate, Expenditure per Capita, Open Unemployment Rate, Gross Regional Domestic Product, Human Development Index. The clustering results identify clustering of regencies and visualized effectively using PCA (Principal Component Analysis)

## Dataset Infomation
- ### Source : Badan Pusat Statistik (BPS) Jawa Timur
- ### Variables :
  - Population (People) : Total number of people in a spesific area
  - Life Expectancy (Years) : Average age a person is expected to live
  - Human Life Span (Years) : Maximum age humans can live
  - Average Years of Schooling (Years) : Average number of years individuals spend in formal education
  - Birth Rate (Per 1000 People) : Number of live births per 1000 people
  - Expenditure per Capita (Rupiah per Person) : Average amount of expenditure per person in a spesific area
  - Open Unemployment Rate (%) : Percentage of the labor force actively seeking but no finding work
  - Gross Regional Domestic Product (Rupiah) : Total value of goods and services produced in a spesific region
  - Human Development Index : Index that measures quality of life based on health, education, and income
- ### Total Data Points : 38 records (total of regencies in East Java)

## Methodology
- ### Clustering Approach
  - Algorithm Used : Self Organizing Map (SOM)
    - SOM is well-suited for clustering districts/cities based on social indicators as it maintains the topological relationships between regions. This ensures that areas with similar social characteristics are positioned closely on the SOM map, allowing for a more intuitive analysis of regional social patterns.
- ### Dimensionality Reduction for Visualization
  - Algorithm Used : PCA (Principal Component Analysis)
    - Used to reduce the five-dimensional data into two principal components for easier interpretation and visualization

## Result and Interpretation
- ### Cluster Result
  ![{636E5FF2-20DF-4FC4-9A1A-2F6064F153A5}](https://github.com/user-attachments/assets/1ac446f9-e36e-4c2f-9a94-622958e58433)


- ### Cluster Interpretation
  - Cluster 1 
    - Dominant Features :
      - **High Birth Rate** (5), suggest rapid population growth, possibly in developing regions
      - **High Open Unemployment** (7), indicates economic instability and lack of job opportunities
      - **Moderate to High Average Years of Schooling** (4), reflects a relatively educated population, though employment opportunities remain a challenge
      - **Moderate Human Life Span** (3), suggests reasonable healthcare service but potential disparities
      - **Moderate Gross Regional Domestic Product** (8), implies that economic conditions are developing but not yet optimal
    - Interpretation : This cluster represents regions with high population growth and a relatively educated workforce but facing economic struggles and unemployment challenges. Although some progress is visible in education, job opportunities and economic stability need significant improvement
 - Cluster 2
   - Dominant Features :
     - **High Population** (1), these areas are densely populated, possibly urban centers or industrial hubs
     - **High Gross Regional Domestic Product** (8), indicates strong economic activity and financial stability
     - **High Human Development Index** (9), suggests good access to healthcare, education, and social services
     - **High Average Years of Schooling** (4), reflects a well-educated workforce, likely contributing to regional economic success
     - **High Expenditure per Capita** (6), implies higher living standards and strong consumer spending power
   - Interpretation : This cluster represents developed regions with strong economic activity, high education levels, and better overall living conditions. These areas are likely to be urban centers with high employment opportunites and significant economic output
 - Cluster 3
   - Dominant Features :
     - **High Open Unemployment** (7), indicates a struggling labor market and job scarcity
     - **High Human Life Span** (3) and **High Life Expectancy** (2), suggests good healthcare service and overall well being
     - **High Birth Rate** (5), suggests a growing population, which may require better infrastructure and economic policies
     - **Moderate Population** (1), these regions are moderately populated but could be expanding
   - Interpretation : This cluster represents regions with strong healthcare systems and a growing population but facing economic challenges due to high unemployment rates. While the quality of life is good, economic stability and job opportunities need attention
  
- ### Conclusion
  - Cluster 1 : 24 regions in East Java are Developing Areas
  - Cluster 2 : 12 regions in East Java are Prosperous Urban Centers
  - Cluster 3 : 2 regions in East Java are Well-being focused but Economically Challenged Areas)

- ### Strategic Recommendations
  - Cluster 1 : Requires job creation programs, economic diversification, and infrastructure investment to support population growth
  - Cluster 2 : Can serve as economic hubs and should focus on sustainable urban development and innovation
  - Cluster 3 : Needs economic revitalization efforts, such as skill development, employment opportunities, and industrial investment

  - ### Cluster Visualization
    ![{77C22D16-A588-4761-9598-A025B825D917}](https://github.com/user-attachments/assets/fc1421dc-5060-47ec-b41c-bc7d4ceb0394)
    - Color-code clusters :
      - Blue : Cluster 1
      - Orange : Cluster 2
      - Green : Cluster 3

## Limitations
- The analysis is limited to social indicator data from regions in East Java in 2022

## Evaluation

The clustering results obtained still have limitations in accurately reflecting real-world conditions. This may be due to constraints in the variables used, data quality, or model parameters applied. Therefore, further evaluation is needed, including validation with additional data or a more comprehensive analytical approach, to ensure that the results are more accurate and representative of actual conditions.
