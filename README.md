# Machine Learning Projects:


## Movie Recommendation:

We'll start by loading up the [MovieLens dataset](https://movielens.org).
Using Pandas, we can very quickly load the rows of the u.data and u.item files that we care about, 
and merge them together so we can work with movie names instead of ID's. (In a real production job, 
we'd stick with ID's and worry about the names at the display layer to make things more efficient. 
But this lets us understand what's going on better for now.)

## Movie Review (Sentiment Analysis):

With the rise of online social media platforms like Twitter, Facebook and Reddit, and the proliferation of customer reviews on sites like Amazon and Yelp, we now have access, more than ever before, to massive text-based data sets! They can be analyzed in order to determine how large portions of the population feel about certain products, events, etc. This sort of analysis is called _sentiment analysis_. In this project we will build an end-to-end sentiment classification system from scratch.

The dataset we are going to use is very popular among researchers in Natural Language Processing, usually referred to as the [IMDb dataset](http://ai.stanford.edu/~amaas/data/sentiment/). It consists of movie reviews from the website [imdb.com](http://www.imdb.com/), each labeled as either '**pos**itive', if the reviewer enjoyed the film, or '**neg**ative' otherwise.

Maas, Andrew L., et al. [Learning Word Vectors for Sentiment Analysis](http://ai.stanford.edu/~amaas/data/sentiment/). In _Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies_. Association for Computational Linguistics, 2011.

