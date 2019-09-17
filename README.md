# Advanced-lane-lines-detection
Working on advance lane lines detection for self-driving car.use OpenCV to detect lane lines in the image. lane lines detection is one of the important parts in the self-driving car, it keeps the car in the center of the lane. To detect lane, first of all, we need to remove all unnecessary information from the image. Apply some thresholding techniques, color and gradient to make lane lines clear in the image then apply perspective transformation for making the left and the right lane line parallel to each other.

## Perspective Transformation

#### Before 
![](https://github.com/aayushrai/Advanced-lane-lines-detection/blob/master/Some%20basics/image/before_perspective.png)

#### After
![](https://github.com/aayushrai/Advanced-lane-lines-detection/blob/master/Some%20basics/image/after_perspective.png)

## Color and Gradient

#### Before 
![](https://github.com/aayushrai/Advanced-lane-lines-detection/blob/master/Some%20basics/image/before_perspective.png)

#### After
![](https://github.com/aayushrai/Advanced-lane-lines-detection/blob/master/Some%20basics/image/after_color_gradient.png)
