# ML_TermP_Movie_Recommendation

## Used Dataset
the movies dataset - https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset<img width="347" alt="image" src="https://user-images.githubusercontent.com/98442485/204256861-0973a87d-4fe0-47cc-88c6-3038da041147.png">

## Function definition (and description)
def apriori_kmeans(user_input):</br>
    apriori_kmeans_result = []</br>
    // ...</br>
    return apriori_kmeans_result</br>
</br>
def content_based(user_input):</br>
    content_based_result = []</br>
    // ...</br>
    return content_based_result</br>
</br>
def collaborate(user_input):</br>
    collaborate_result = []</br>
    // ...</br>
    return collaborate_result</br>
</br>
def MainFunction(apriori_KMeans_input, content_based_input, collaborate_input):</br>
    final_result = []</br>
    final_result += apriori_kmeans(apriori_KMeans_input)</br>
    final_result += content_based(content_based_input)</br>
    final_result += collaborate(collaborate_input)</br>
    print(final_result)</br>
</br>
</br>
=================================================</br>
// Main </br>
// apriori_KMeans_input</br>
input1 = []</br>
// content_based_input</br>
input2 = []</br>
// collaborate_input</br>
input3 = []</br>
</br>
// Run!</br>
MainFunction(apriori_KMeans_input=input1, content_based_input=input2, collaborate_input=input3)</br>

## Architecture
<img width="748" alt="스크린샷 2022-11-27 오전 5 19 12" src="https://user-images.githubusercontent.com/98442485/204107601-9c7b112b-6c9f-4ffc-8510-3a2b0330201b.png">

## Reference
https://www.youtube.com/watch?v=6TP51jvjLsE&t=2087s</br>
https://github.com/lsjsj92/recommender_system_with_Python</br>
https://big-dream-world.tistory.com/69</br>
https://medium.com/recombee-blog/machine-learning-for-recommender-systems-part-1-algorithms-evaluation-and-cold-start-6f696683d0ed</br>
<img width="706" alt="image" src="https://user-images.githubusercontent.com/98442485/204258006-1832e8b1-7145-498c-84ba-3971d74e4371.png">
