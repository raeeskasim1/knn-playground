# KNN Playground

A tiny interactive machine-learning lab. Add two classes of points, place a query, and see its nearest neighbours vote.

https://raeeskasim1.github.io/knn-playground/

## Try it

- Click **Predict**, **Add A**, or **Add B** before clicking the plot.
- Change **k** to redraw the decision regions.
- Use the coordinate form for exact inputs or keyboard access.
- Clear the data, build your own dataset, and undo changes.

## How it works

The classifier uses Euclidean distance on two features normalized to 0–1. It sorts training points by distance, selects up to k neighbours, and uses an unweighted majority vote. Ties are resolved using the closest neighbour. Background cells are classified at their centres, so the boundary is a visual approximation.

The voting fraction is not a calibrated probability. This is a small educational implementation, not a production model.
