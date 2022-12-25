# Video-scaling-HLS-implementation

Video scaling is most efficiently accomplished in high-volume systems dealing with standardised image sizes, such as HD television, by using application-specific standard products (ASSPs). Many video applications, however, require solutions that can handle configurable image sizes and varying levels of quality, such as video surveillance, broadcast display and monitoring, video conferencing, and specialty displays. 
This frequently necessitates the development of custom scaling algorithms. 


Video scaling, whether upscaling or downscaling, is the
process of generating pixels that did not exist in the original
image.

There are many methods for generating new pixels: thesimplest is called the nearest neighbor method, or 11 interpolation. In this method a new pixel value is simply equal to the value of the preceding pixel. This is the simplest example of
scaling and requires minimal hardware resources since no
calculations have to be done
In a slightly more sophisticated approach, called bilinear
scaling, a new pixel is equal to the average of the two neighboring
pixels in both the vertical and horizontal dimensions.
