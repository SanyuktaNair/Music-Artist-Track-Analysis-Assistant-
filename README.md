# Music-Artist-Track-Analysis-Assistant-
Tools & Tech: R, Power BI, Amazon Redshift, SQL

Overview:
This project focused on analyzing global music trends over time to understand what makes songs and genres popular. Using Spotify data spanning from 1936 to 2020, the goal was to create a comprehensive tool that could help artists, producers, and marketers make informed decisions about music production and promotion.

Key Contributions:

    Data Pipeline & Storage: Over 150,000 Spotify tracks were cleaned and stored using Amazon Redshift for scalable querying and data warehousing.

    Statistical Analysis: Conducted hypothesis testing (t-tests, z-tests, and ANOVA) to evaluate how features like tempo, energy, danceability, and loudness vary across genres and influence listener engagement.

    Regression Modeling: Built regression models to analyze the relationship between song features and popularity scores, providing insight into which characteristics are most predictive of success.

    Clustering for Personalization: Applied k-means clustering to group tracks based on audio features, enabling genre-based recommendations and user-persona classification.

    Interactive Dashboard: Designed a Power BI dashboard with rich visualizations showing:

        Evolution of popular genres over decades

        Feature distributions per genre

        Track recommendations based on cluster analysis

        Region-wise popularity trends (optional future enhancement)

Impact:
This assistant can serve as a decision-support tool for stakeholders in the music industry, offering data-backed insights into which kinds of tracks are more likely to resonate with different audiences. It also lays the foundation for building personalized recommendation systems.
