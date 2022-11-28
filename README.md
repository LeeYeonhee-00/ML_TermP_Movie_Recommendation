# ML_TermP_Movie_Recommendation

## Used Dataset
the movies dataset - https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset<img width="347" alt="image" src="https://user-images.githubusercontent.com/98442485/204256861-0973a87d-4fe0-47cc-88c6-3038da041147.png">

## Function definition (and description)
def apriori_kmeans(user_input):
    apriori_kmeans_result = []
    // ...
    return apriori_kmeans_result

def content_based(user_input):
    content_based_result = []
    // ...
    return content_based_result

def collaborate(user_input):
    collaborate_result = []
    // ...
    return collaborate_result

def MainFunction(apriori_KMeans_input, content_based_input, collaborate_input):
    final_result = []
    final_result += apriori_kmeans(apriori_KMeans_input)
    final_result += content_based(content_based_input)
    final_result += collaborate(collaborate_input)
    print(final_result)


=================================================
// Main 
// apriori_KMeans_input
input1 = []
// content_based_input
input2 = []
// collaborate_input
input3 = []

// Run!
MainFunction(apriori_KMeans_input=input1, content_based_input=input2, collaborate_input=input3)

## Architecture
<img width="748" alt="스크린샷 2022-11-27 오전 5 19 12" src="https://user-images.githubusercontent.com/98442485/204107601-9c7b112b-6c9f-4ffc-8510-3a2b0330201b.png">

## Reference
https://www.youtube.com/watch?v=6TP51jvjLsE&t=2087s</br>
https://github.com/lsjsj92/recommender_system_with_Python</br>
https://big-dream-world.tistory.com/69</br>
https://medium.com/recombee-blog/machine-learning-for-recommender-systems-part-1-algorithms-evaluation-and-cold-start-6f696683d0ed</br>
<img width="706" alt="image" src="https://user-images.githubusercontent.com/98442485/204258006-1832e8b1-7145-498c-84ba-3971d74e4371.png">
