# FIFA-20-Player-Analysis-Clusterin
FIFA 20 player data analysis and clustering using K-Means, Agglomerative, and DBSCAN
Objective

Segment FIFA 20 players into meaningful groups based on their skill attributes to support football scouting, recruitment, and squad planning decisions.

Dataset

18,278 player records with 104 features (demographics, physical attributes, technical skills, wages, club info, performance ratings).

Workflow
Removed columns with excessive missing values (national team info, loan status, traits)
Performed EDA — top talent-producing countries, peak performance age trends
Applied StandardScaler for feature scaling
Used the Elbow Method and PCA for dimensionality analysis and to determine the optimal number of clusters
Compared three clustering algorithms using the Silhouette Score
Results
Algorithm	Silhouette Score
K-Means	0.212
Hierarchical Clustering	0.198
DBSCAN	0.083
Cluster Interpretation
Cluster	Profile	Likely Position
0	High dribbling, acceleration, crossing	Wingers
1	High finishing, positioning, shot power	Strikers
2	High interceptions and tackling	Defenders
3	Balanced passing and vision	Midfielders
4	Average across most skills	Squad/Rotation players
Business Recommendations
Use clusters to identify players with similar playing styles for recruitment
Analyze squad composition to spot gaps in team structure
Compare youth players against established clusters for development planning
Use cluster insights for transfer market valuation
