## Digital Cameras and tuning

Digital cameras are widely employed in numerous applications, such as 
1. advanced still cameras,
2. camcorders,
3. camera telephones, and 
4. video observations.

The camera which captures sensible images with adjusted parameters:

```markdown
saturation,
brightness,
contrast,
```
and so forth bringing about top notch picture is driving in the market.

## Camera frameworks

```markdown
The objective of a Camera framework is to capture a scene and imitate the caught scene in a digital format.
The Camera Sensor incorporates lens, color filter array (Bayer) and a image sensor.
The Bayer sensor filters the light by wavelength range, such that the separate filtered intensities include information about the color of light which are captured in the light bucket and then the ADC converts the electronic signals into digital signals recreating the RAW picture.
The block diagram shows how a scene is seen on the camera sensor and how it is handled to get a raw image from the image sensor.
```
![camera-sensor](/digital_camera/docs/assets/images/camera_sensor.png)

## Phases in camera tuning

Camera Tuning is a critical step in developing a digital camera product.
It is a procedure to adjust and set camera working boundaries that create excellent pictures.
This can be a complex strategy which covers the accompanying,

```markdown
Initial / Objective Tuning
3A Tuning
Fine /  Subjective Tuning
Image quality analysis
```

## Camera Initial tuning

The image processor, which takes raw data produced by the camera sensor and generates a
digital image which can be viewed or experience further handling, 
is a series of specialized algorithms that changes the image continuously in real-time.

The Initial tuning of the camera sensor goes through the following procedures, 
1. Acquisition of images at controlled illumination with different charts and objects based on the test cases.
2. Tuning (an ISP) or adjusting an image signal processor to optimize the image quality. 

![isp](/digital_camera/docs/assets/images/isp.png)
