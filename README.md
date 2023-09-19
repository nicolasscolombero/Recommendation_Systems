Movie Recommendation System with Collaborative Filtering

This project revolves around the development of a Movie Recommendation System using Collaborative Filtering techniques. Recommendation systems are algorithms that provide personalized suggestions to users based on their preferences and behaviors. In this context, we explore Collaborative Filtering as a means to enhance user experience on various platforms, including online stores, movie databases, and job search engines.

The core idea behind Collaborative Filtering is to make movie recommendations by leveraging user data. Specifically, we utilize a ratings dataframe containing user IDs, movie IDs, ratings, and timestamps. The timestamps are removed to optimize memory usage. Subsequently, we extract movie IDs from the movies dataframe and merge them with the input data. Unnecessary columns are dropped to conserve memory space.

Upon preparing the input data, we implement Collaborative Filtering to generate movie recommendations. The top 20 movie recommendations are sorted and displayed. This project showcases the practical application of recommendation systems using Python and the Pandas library.

Feel free to explore the code and customize it for your own use case. This project was inspired by a course on Cognitive Class by IBM.

Getting Started:

    Clone this repository.
    Install the required dependencies.
    Execute the provided Jupyter Notebook to explore the Movie Recommendation System.

Happy movie recommendation exploration!

Please adapt and include any additional information or instructions specific to your project as needed.
