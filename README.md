# Simple Inference Scripts for YOLO with OpenCV (With Mask Output Option)

I forked a YOLOv4 inference script for both video and image files, easy to use and not complicated.

The edits in this fork add a 'mask_output' cropping the labels onto a black background.

## Example Usage

``` python yolo_image.py -i street.jpg -o output.jpg -m mask_output.jpg ```

``` python yolo_video.py -i video.mp4 -o video_out.avi -m mask_output.jpg```

## Normal Output
![output](https://user-images.githubusercontent.com/38813142/160272575-70155506-808f-47f7-a663-6758adcead7b.jpg)

## Mask Output
![mask](https://user-images.githubusercontent.com/38813142/160272592-051c772c-1f2a-4122-a81d-b0c5b124859a.jpg)

## TODO

- [ ] Add custom training script

## References
<https://github.com/opencv/opencv/blob/master/samples/dnn/object_detection.py>
<https://www.pyimagesearch.com/2020/06/01/opencv-social-distancing-detector/>
