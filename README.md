# rice data
 After appropriate cleaning process to data, rice type prediciton was made with knn, logistic regression and random forest methods.
 The cleaning step was applied in different notebook and the data which appropriate to modelling process was exported.
 
 ## Features:
 id: Unique ID of the rice sample
 Area Extent: Number of pixels within the boundaries of the rice grain and the ratio of the region formed by the rice grain to the bounding box pixels. separated by a   delimiter
 Perimeter: Circumference around the boundaries of the rice grain
 Major Minor Axis Length: The main and small axis lengths, separated by a delimiter
 Eccentricity: Eccentricity of the rice grain
 Convex Area: Pixel count of the smallest convex Shell of the region formed by the rice grain
 outcome: The type of rice (1: Osmancik - 0: Cammeo)
