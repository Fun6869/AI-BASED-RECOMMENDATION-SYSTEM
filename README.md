# AI-BASED-RECOMMENDATION-SYSTEM

**COMPANY: CODETECH IT SOLUTIONS**

**NAME: Patil Mayuresh Pratap**

**INTERN ID:CT08ICW**

**DOMAIN:JAVA**

**BATCH DURATION:December 30th, 2024 to January 30th, 2025**

**MENTOR NAME:NEELA SANTOSH**

**Libraries used**

**1.java.io.BufferedReader:**
Used for reading text from a character-based input stream. It provides an efficient way to read lines from a file.

**2.java.io.BufferedWriter:**
Used for writing text to a character-based output stream. It provides an efficient way to write characters to a file.

**3.java.io.FileReader:**
Used to read the data from the input file (u.data). It’s used as the underlying file input stream for the BufferedReader.

**4.java.io.FileWriter:**
Used to write data to the output file (movies.csv). It’s used as the underlying file output stream for the BufferedWriter.

**5.java.io.IOException:**
This exception is thrown in case of any errors during file I/O operations.

**6.org.apache.mahout.cf.taste.common.TasteException :**
Exception handling specific to Mahout's Collaborative Filtering library (Mahout CF).

**7.org.apache.mahout.cf.taste.impl.common.LongPrimitiveIterator :**
This is an iterator used in Mahout to iterate over long (primitive) values, specifically used for iterating through the items in the dataset.

**8.org.apache.mahout.cf.taste.impl.model.file.FileDataModel :**
A concrete implementation of the DataModel interface, this class is used to read and represent the user-item interaction data from a file (in this case, "movies.csv"). The data in this file is expected to be in a specific format suitable for use with Mahout's recommendation algorithms.

**9.org.apache.mahout.cf.taste.impl.recommender.GenericItemBasedRecommender :**
A recommender system implementation that recommends items based on the similarity of items. This class is used to generate item-based recommendations, which is the core functionality of this code.

**10.org.apache.mahout.cf.taste.impl.similarity.TanimotoCoefficientSimilarity :**
A class that implements item similarity calculation using the Tanimoto Coefficient, which is a measure of similarity between sets. It's typically used to compare binary (or presence/absence) features of items. In this case, it's used to measure similarity between items based on user interactions.

**11.org.apache.mahout.cf.taste.model.DataModel :**
The Mahout interface representing the data model. The FileDataModel class implements this interface, representing a collection of user-item interactions, which the recommender algorithm can use to make recommendations.

**12.org.apache.mahout.cf.taste.recommender.RecommendedItem :**
Represents a recommended item. This class contains the item ID and the predicted score or value for that recommendation (e.g., how much a user might like the item).

**13.org.apache.mahout.cf.taste.similarity.ItemSimilarity :**
Interface for calculating item similarity. TanimotoCoefficientSimilarity is a specific implementation of this interface, used to compute the similarity between items.

**HOW TO RUN**

- First run MovieDataConvert.java; code provided in MovieDataConvert is a data conversion script that reads data from a file (likely in a tab-separated format) and converts it into a comma-separated format. Specifically, it processes the input data file (u.data) and outputs a CSV file (movies.csv).

- After this we will get movies.csv file which will be used for item reccomendation

- Then run ItemRecommend.java which is a basic item-based collaborative filtering recommender system. The purpose of the code is to recommend items to users based on the similarity between the items themselves.

**OUTPUT**

![Screenshot 2025-01-21 195254](https://github.com/user-attachments/assets/35cca16e-8f0d-48f6-8b9e-9b71301f9cc7)



