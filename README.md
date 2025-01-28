# InformSupply: Integrating Knowledge Graphs with Traditional BI Tools
Master's Consultancy Project

## Project Overview
This project was conducted as part of my Master's program and involved collaboration with **InformSupply**, a client focusing on transforming business data management using innovative knowledge graph technology. The aim was to integrate knowledge graphs with traditional BI tools, such as Power BI, to enhance data visualization and uncover hidden relationships. The project transformed RDF data into a star schema for seamless integration, enabling advanced analysis using both networked and traditional visuals.

---

## Key Findings 
By combining traditional performance metrics with relationship-driven networked graphs in a single dashboard, users gain a clear and comprehensive view of the data, revealing deeper insights and connections.

## Key Features
- **RDF Data Transformation**: Converted RDF data into a star schema, aligning it with relational database structures for BI integration.
- **Power BI Integration**: Explored multiple integration methods, selecting CSV export as the final approach for performance optimisation.
- **Interactive Dashboards**: Built two dashboards, one using ZoomCharts and another with Python NetworkX, to showcase networked graphs alongside traditional visuals.
- **Visualization Methods Comparison**: Summarised the strengths and limitations of ZoomCharts, NetworkX, and GraphDB built-in visuals.
- **User Interaction Testing**: Conducted testing to validate usability and collect feedback from users. Participants valued the simplicity of traditional charts for straightforward tasks and appreciated the depth provided by networked graphs for more complex analyses.

## Project Posters and Brochure for Expo
- [Technical Poster](https://github.com/Brenda-Chuang/Integrating-Knowledge-Graphs-with-Traditional-BI-Tools/blob/main/InformSupply%20Project%20Poster_finalised_2024.10.09.pdf)
- [Emotional Poster](https://github.com/Brenda-Chuang/Integrating-Knowledge-Graphs-with-Traditional-BI-Tools/blob/main/Emotional%20Infograph%20-%20InformSupply_2024.10.09.pdf)
- [Brochure for Guests](https://github.com/Brenda-Chuang/Integrating-Knowledge-Graphs-with-Traditional-BI-Tools/blob/main/InformSupply_Capstone%20Project_Brochure_2024.10.09.pdf)

## Project Objectives
The purpose of this project is to explore integration and visualisation methods for combining knowledge graphs with traditional BI tools. By using an open-source movie dataset, the project provides a practical demonstration of how RDF data can be transformed, integrated, and visualised in Power BI.

## Dataset
Dataset Used: An open-source [movie dataset](https://github.com/Brenda-Chuang/Integrating-Knowledge-Graphs-with-Traditional-BI-Tools/blob/main/movies.ttl) was selected to simulate real-world scenarios and provide a clear context for testing integration and visualisation approaches.
The dataset includes details about movies, actors, genres, and related attributes, offering a rich source for evaluating visualisation methods.

---

## My Role
### **Technical Contributions**
- Explored and developed Power BI integration using multiple methods.
- Designed and implemented the RDF-to-star schema transformation process and data modelling.
- Built an interactive Power BI dashboard, using ZoomCharts visuals for networked graphs in all report pages.

### **Project Leadership**
- Led the project team, managed timelines, and ensured deliverables aligned with client goals.
- Collaborated with stakeholders, including the client and supervisor, to achieve project objectives.

---

## Technical Details
### **Technologies Used**
- **RDF Data**: GraphDB
- **Data Transformation**: SPARQL queries, Python
- **BI Tool**: Power BI
- **Star Schema Development**: Relational database modeling

### **Implementation Steps (My Contributions Only)**
1. **Integration Method Exploration**:
   - Evaluated:
     - JDBC-ODBC Gateway
     - Python Script Wrapping SPARQL Queries. <br/>
       Documented the process in [Python Script Wrapping the SPARQL query.ipynb](https://github.com/Brenda-Chuang/Integrating-Knowledge-Graphs-with-Traditional-BI-Tools/blob/main/Python%20Script%20Wrapping%20the%20SPARQL%20query.ipynb).
     - CSV Export from GraphDB (Selected Method)
2. **Understanding RDF Ontology**:
   - Analysed and mapped ontology relationships for star schema development.
   ![image](https://github.com/user-attachments/assets/1d01df63-6da9-4620-b0fb-b1caeb97fa4b)

3. **Data Transformation**:
   - Transformed RDF data into a star schema using Python and SPARQL queries.
4. **Data Modelling**:
   - Developed a star schema in Power BI.<br/>
   ![image](https://github.com/user-attachments/assets/ca1c930d-1004-47f0-9875-69afdf248d8f)

5. **Dashboard Design**:
   - Built the Power BI dashboard, including four report pages integrating traditional and networked graph visuals using ZoomCharts.
   - Dashboard demo video. <br/>
     [![Watch the video](https://img.youtube.com/vi/W6pE34_IT0A/0.jpg)](https://www.youtube.com/watch?v=W6pE34_IT0A) <br/>
     Click the image above to watch the project demo on YouTube.

    - Page 1: Actor Performance and Centrality <br/>
     ![image](https://github.com/user-attachments/assets/1dd47013-9a37-4016-9b22-76d6d0b8fa05) <br/>
     This page combines traditional bar and column charts with a networked visual to analyse actors with the highest comment counts and their centrality in the movie network. The bar column highlights actors with the most comments, while the bar charts show the centrality rank of top actors. The networked graph adds value by showcasing their connections to specific movies and other actors, providing insights into how their prominence in the network compares to their comment performance.

    - Page 2: Actor Collaborations Across Movies <br/>
     ![image](https://github.com/user-attachments/assets/d9147df9-8bd9-4d71-914c-78960f0406f6) <br/>
     This page uses traditional charts to show which actors have acted in the most movies. The networked graph enhances the analysis by revealing actor collaborations within specific movie genres, visually mapping how frequently they co-star in the same movies. Together, they offer a deeper understanding of the relationships between actors and their levels of participation in different genres.

    - Page 3: Actor Versatility <br/>
     ![image](https://github.com/user-attachments/assets/0b9d0345-153d-4cee-8f3a-856836f0462a) <br/>
     The bar chart summarises the number of genres top actors have participated in, while a heatmap visualises how many times they appeared in each genre. The networked graph adds another dimension, showing clusters of actors organised by genre participation, which helps identify which actors are more versatile or specialized in certain genres. This combination offers both a high-level overview and a detailed look at actor-genre relationships. 

    - Page 4: Genre Synergies and Engagement <br/>
     ![image](https://github.com/user-attachments/assets/3319c736-c73e-43ed-814f-12e434d3fc25) <br/>
     This page presents genre-movie connections across countries using bar and pie charts to show the most popular movies and genres by comment count. The networked graph maps out the relationships between countries, genres, and movies, providing a comprehensive view of how different genres perform across various countries.

---
## Visualisation Methods Comparison for Reporting
- Summary of Strengths and Limitations of Visualisation Methods
  ![image](https://github.com/user-attachments/assets/05f50ebc-24ab-40d6-97ea-903fc081bf96)



