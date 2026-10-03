# KNN Playground

A tiny interactive machine-learning lab. Add two classes of points, place a query, and see its nearest neighbours vote.

## Run

Open `index.html` in a modern browser. No installation, server, internet connection, API key, or build step is required. HTML, CSS, and JavaScript are all in that file.

## Try it

- Click **Predict**, **Add A**, or **Add B** before clicking the plot.
- Change **k** to redraw the decision regions.
- Use the coordinate form for exact inputs or keyboard access.
- Clear the data, build your own dataset, and undo changes.

## How it works

The classifier uses Euclidean distance on two features normalized to 0–1. It sorts training points by distance, selects up to k neighbours, and uses an unweighted majority vote. Ties are resolved using the closest neighbour. Background cells are classified at their centres, so the boundary is a visual approximation.

The voting fraction is not a calibrated probability. This is a small educational implementation, not a production model.

## Practice extension

Add distance-weighted voting and compare the boundary with the current majority vote.

## Publish

Create a GitHub repository named `knn-playground` and upload these two files at its root. Optionally enable GitHub Pages for the root of your main branch.
