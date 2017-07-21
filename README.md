# Similarity_Search
Similarity Search using Histogram Normalization

Feature extraction is to extract the color histogram value from an image. The color histogram
for an image is constructed by quantizing the colors within the image and counting the number of pixels of each color.
Then we take a summation of it and find the mean and standard deviation from the color histogram. Finally it stored
in a 1D array. This value is calculated for every image in the database. 

Various metrics have been used to compare histogram between images. The metrics used are :
1. Correlation 
2. Chi square
3. Intersect
4. Bhattacharyya distance/ Hellinger
