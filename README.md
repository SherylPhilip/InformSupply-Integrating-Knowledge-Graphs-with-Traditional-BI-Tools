# InformSupply: Integrating Knowledge Graphs with Traditional BI Tools
Master's Consultancy Project

## **Project Overview**

This consultancy project, undertaken as part of my Master’s program, involved collaborating with **InformSupply**, an organization focused on revolutionizing business data management through knowledge graph technology. The goal was to bridge the gap between knowledge graphs and traditional business intelligence (BI) tools like Power BI. By transforming RDF data into a star schema, the project enabled seamless integration and advanced data analysis through both networked visualizations and traditional BI dashboards.
---

## Key Findings 
The integration of traditional performance metrics with relationship-driven network graphs within a single dashboard provided users with a unified view of data, uncovering deeper insights and connections that are often overlooked in conventional analysis.

## Key Features
- **RDF Data Transformation**: Converted RDF data into a star schema format, enabling alignment with relational database structures and optimized compatibility with BI tools.
- **Power BI Integration**: Explored multiple integration methods, ultimately selecting CSV export from GraphDB for its simplicity and performance benefits.
- **Interactive Dashboards**: Developed two interactive dashboards—one utilizing ZoomCharts and the other employing Python NetworkX—to display both traditional and networked graph visuals side by side.
- **Visualization Methods Comparison**: Analyzed the strengths and limitations of various visualization tools, including ZoomCharts, NetworkX, and GraphDB’s built-in graph visuals.
- **User Interaction Testing**: Conducted comprehensive usability testing to validate dashboard effectiveness. Feedback revealed that users appreciated the simplicity of traditional charts for basic queries and the depth of network graphs for exploring complex relationships.

## Project Posters and Brochure for Expo
- [Technical Poster](https://github.com/SherylPhilip/InformSupply-Integrating-Knowledge-Graphs-with-Traditional-BI-Tools/blob/main/InformSupply%20Project%20Poster_finalised_2024.10.09.pdf)
- [Emotional Poster](https://github.com/SherylPhilip/InformSupply-Integrating-Knowledge-Graphs-with-Traditional-BI-Tools/blob/main/Emotional%20Infograph%20-%20InformSupply_2024.10.09.pdf)
- [Brochure for Guests](https://github.com/SherylPhilip/InformSupply-Integrating-Knowledge-Graphs-with-Traditional-BI-Tools/blob/main/InformSupply_Capstone%20Project_Brochure_2024.10.09.pdf)

## Project Objectives
The primary objective was to explore and demonstrate methods for integrating knowledge graphs with traditional BI tools. Using an open-source movie dataset, the project provided a practical showcase of how RDF data could be transformed, integrated, and visualized effectively in Power BI.

## Dataset
Dataset Used: An open-source [movie dataset](https://github.com/SherylPhilip/InformSupply-Integrating-Knowledge-Graphs-with-Traditional-BI-Tools/blob/main/movies.ttl) was selected to simulate real-world scenarios and provide a clear context for testing integration and visualisation approaches.
The dataset included rich information about movies, actors, genres, and their relationships, offering a comprehensive test case for evaluating integration and visualization approaches.

---

## My Role
### **Technical Contributions**
- **GraphDB Deployment**: Configured GraphDB in Docker for efficient RDF data management and SPARQL querying.
- **RDF Data Transformation**: Converted RDF data into a star schema using SPARQL and Python for seamless Power BI integration.
- **Interactive Dashboards**: Developed Power BI dashboards with Python NetworkX for traditional and networked visualizations.
- **Visualization Implementation**: Created and embedded NetworkX network graphs in Power BI to showcase actor collaborations and genre connections.


### **Quality Managerp**
As the Quality Manager, I ensured the project adhered to high standards across all phases, from planning to execution. My responsibilities included:

- **Task Monitoring** : Oversaw task progress to ensure timely completion of milestones, such as GraphDB deployment, data transformation, and dashboard creation.
- **Documentation and Consistency** : Maintained comprehensive and organized documentation, ensuring clear communication of methods, progress, and findings to the team and stakeholders.
- **User Testing Oversight**: Designed and facilitated the user interaction testing process, ensuring actionable feedback was collected and incorporated into the dashboards for usability improvements.
- **Expo Readiness** : Verified the quality and completeness of all deliverables, including posters, dashboards, and brochures, for a professional and engaging presentation at the Expo.

---

## Technical Details
### **Technologies Used**
- **RDF Data**: GraphDB
- **Data Transformation**: SPARQL queries, Python
- **BI Tool**: Power BI
- **Star Schema Development**: Relational database modeling

### **Implementation Steps (My Contributions and teammate(Brenda Chuang))**
1. **Integration Method ExplorationBrenda Chuang)**:
   - Evaluated:
     - JDBC-ODBC Gateway
     - Python Script Wrapping SPARQL Queries. <br/>
       Documented the process in [Python Script Wrapping the SPARQL query.ipynb](https://github.com/SherylPhilip/InformSupply-Integrating-Knowledge-Graphs-with-Traditional-BI-Tools/blob/main/Python%20Script%20Wrapping%20the%20SPARQL%20query.ipynb).
     - CSV Export from GraphDB (Selected Method)
2. **Understanding RDF Ontology**:
   - Analysed and mapped ontology relationships for star schema development.  
![image][403739137-1d01df63-6da9-4620-b0fb-b1caeb97fa4b](https://github.com/user-attachments/assets/dd121474-59d5-4523-97fa-1a23f75ea6fe)

3. **Data Transformation**:
   - Transformed RDF data into a star schema using Python and SPARQL queries.
4. **Data Modelling**:
   - Developed a star schema in Power BI.<br/>
 ![403741708-ca1c930d-1004-47f0-9875-69afdf248d8f](https://github.com/user-attachments/assets/d93b6072-dede-45e4-be51-f0e187555211)


5. **Dashboard Design for NetworkX Visualizations**:
   - Built the Power BI dashboard, including four report pages integrating traditional and networked graph visuals using Networkx.
   - Dashboard demo video.
     [![Watch the video](https://youtu.be/0tWV6iNT5uw?si=LpQ74RMXMau5pGMV)
     Click the image above to watch the project demo on YouTube.

    - Page 1: Actor Performance and Centrality 
  <img width="415" alt="Picture 5" src="https://github.com/user-attachments/assets/25038816-f104-4dd3-ba5e-bafe3c2ae9c2" />
     This page combines traditional bar and column charts with a networked visual to analyse actors with the highest comment counts and their centrality in the movie network. The bar column highlights actors with the most comments, while the bar charts show the centrality rank of top actors. The networked graph adds value by showcasing their connections to specific movies and other actors, providing insights into how their prominence in the network compares to their comment performance.

    - Page 2: Actor Collaborations Across Movies 
  <img width="415" alt="Picture 2" src="https://github.com/user-attachments/assets/4db332f1-102f-40f2-ac2d-569d11252ece" />
This page features a networked graph that visualizes the collaboration network of the top 5 actors, including their comment counts and connections across movies. The graph highlights the strength of collaborations with node size and edge thickness, offering a clear view of actor popularity and co-star relationships.

    - Page 3: Actor Versatility 
<img width="415" alt="Picture 3" src="https://github.com/user-attachments/assets/5ea57f7c-49fe-4c49-a2af-3e87a4e2d5d9" />
This visualization explores actors' versatility across genres and roles. The network graph links actors to movies, genres, and countries, with nodes representing their genre count and role type. This design provides insights into the breadth of an actor's contributions and their connections across the dataset.

    - Page 4: Genre Synergies and Engagement 
    <img width="415" alt="Picture 4" src="https://github.com/user-attachments/assets/f04152d0-69ed-4e38-a588-74501647c619" />
This graph focuses on genre popularity and movie engagement. Movies with the highest comment counts are linked to their genres and countries, with node size reflecting comment weight. The network reveals regional genre trends and high-performing movies in an optimized layout.
---
## Visualisation Methods Comparison for Reporting
- Summary of Strengths and Limitations of Visualisation Methods
  ![image]![403794555-05f50ebc-24ab-40d6-97ea-903fc081bf96](https://github.com/user-attachments/assets/a001b3dc-8b26-46be-9f71-c6ea31502b33)



