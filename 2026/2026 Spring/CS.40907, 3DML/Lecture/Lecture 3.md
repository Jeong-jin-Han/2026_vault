# Quiz

>[!In PointNet, what is the set of critical points? Given a input point cloud, how can we determine whether a particular point is a critical point?]-
>
>The set of critical points consists of  the points that contribute to the global feature after the symmetric function (max pooling).
>
>A point is a critical point if it achieves the maximum value in at least one dimension after the shared MLP.
>In other words, if removing the point changes any element of the global feature vector, it is a critical point.


>[!When a new point is added to the input point cloud, does it necessarily affect the global feature produce by PointNet? Explain how to determine whether it changes the feature or leaves it unchanged.]-
>
>No, adding a new point does not necessarily change the global feature.
>
>Since PointNet uses max pooling, the global feature only changes if the new point produces a larger value than the current maximum in at least one feature dimension.
>If it does not exceed any existing maximum, the global feature remains unchanged.



