# Machine Learning Projects:

<div class="alert alert-block alert-info">
## Movie Recommendation:
</div>


We'll start by loading up the [MovieLens dataset](https://movielens.org).
Using Pandas, we can very quickly load the rows of the u.data and u.item files that we care about, 
and merge them together so we can work with movie names instead of ID's. (In a real production job, 
we'd stick with ID's and worry about the names at the display layer to make things more efficient. 
But this lets us understand what's going on better for now.)

