# Comprehensive Movie Dataset Analysis

## Project Purpose:
This project aims to offer a detailed analysis of movie datasets extracted from renowned platforms including IMDB, MovieLens, The Numbers, and BoxOffice Mojo. We focus on attributes such as movie details, cast data, box office revenue, along with insights into prominent movie brands and franchises. Another pivotal component is the ETL process, orchestrated using Talend.

## Stack & Tools:
- **Database & Design**: ER/ Studio, SQL Server Developer Edition, Microsoft SQL Server Management Studio
- **ETL Tool**: Talend Real-Time Data Platform 7.1
- **Visualization**: Tableau Desktop, Microsoft PowerBI

## Dataset Sources:
- [IMDB Dataset](https://datasets.imdbws.com/)
- [BoxOffice Mojo Franchise Data](https://www.boxofficemojo.com/franchise/?ref_=bo_nb_fr_secondarytab)
- [BoxOffice Mojo Brand Data](https://www.boxofficemojo.com/brand/?ref_=bo_nb_frs_secondarytab)
- [MovieLens Data](https://grouplens.org/datasets/movielens/25m/)
- [The Numbers Franchise Overview](https://www.the-numbers.com/movies/franchises)
- [Marvel Cinematic Universe on The Numbers](https://www.the-numbers.com/movies/franchise/Marvel-Cinematic-Universe#tab=summary)
- [The Avengers 2012 Box Office Data](https://www.the-numbers.com/movie/Avengers-The-(2012)#tab=box-office)

## Execution Guide:
### **Step 1**: Database Setup in SSMS
Execute the following scripts:
- The Number - stage tables.sql
- stg imdb tables - core tables.sql
- stg imdb tables expanded part 2.sql
- stg_ml_tables.sql

### **Step 2**: Configure Talend 
Launch Talend, then establish your database and input file connections. Ensure connections are active and execute the jobs.

### **Step 3**: Visualization & Reporting
Use Tableau and PowerBI for data visualization. Refer to the Tableau workbook for existing visualizations. More use cases and the Microsoft PowerBI file will be incorporated shortly.

## Learning & Documentation:
- [Tableau eLearning](https://elearning.tableau.com/)
- [Talend Help](https://help.talend.com/reader/KxVIhxtXBBFymmkkWJ~O4Q/8RlpZdAdKhP0IaMHXRV7yw)
- [Talend Official](https://www.talend.com/)
- [MovieLens Dataset Info](https://grouplens.org/datasets/movielens/)

## Connect:
For inquiries, suggestions, or potential collaborations, kindly contact [ankithindrakumar@gmail.com](mailto:ankithindrakumar@gmail.com).
