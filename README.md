# MovieDbKotlin

makes request to the movie database web api using internet permissions and populates
the view using MVVM architecture. from the main activity you search for your desired
movie and if the request comes back with an successful response it loads all the movies
associated with your search in a recycler view. If you click on any movie selection the
full description of the movie displays in a separate fragment. but in Kotlin