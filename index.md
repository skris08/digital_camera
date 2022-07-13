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

## Key perfomance indicators

The ISP (Image Signal Processor) equips these specialized algorithms. These algorithms in the conversion process are known as the Key Performance Indicators (KPI). 
Following are the KPIs for image processing that are equipped by the ISP to deliver a high-quality image,

```markdown
White Balance (WB)
Denoise
Sharpness / Texture detail
Demosaicing
Color Accuracy
Lens Distortion
Dynamic Range
3A 
  Auto Exposure
  Auto Focus
  Auto White Balance 
```

## White Balance (WB)

White balance (WB) is the method of evacuating unrealistic color casts so that 
objects which appear white in person are rendered white in your photo. 
Proper camera white balance must take into consideration the
"color temperature" of a light source, which refers to the relative warmth or coolness of white light.

```markdown
Test Charts used:
Light booth and light meter
18 % Gray Chart
Macbeth Color checker
Bayer AWB tuning
```
![white_balance](/digital_camera/docs/assets/images/white_balance.png)

## Denoise

Noise is a random variation of image density, visible as grain in film and pixel level variations in digital images.
It appears from the photon nature of the light and the thermal energy of heat.

```markdown
Test Charts used:
  Macbeth Color checker
    ABF noise profiling 
    Wavelet noise reduction (WNR) noise profiling
```

![denoise](/digital_camera/docs/assets/images/denoise.jpg)

## Demosaicing

A demosaicing algorithm is a digital image process used to recreate
a full color image from the fragmented color output overlaid with a color filter array (CFA).
Each color channel may permit an alternate frequency of light to pass –
this is predetermined during the camera design.
The algorithm used in the process: 
the nearest-neighbor interpolation which essentially duplicates an adjoining pixel of a similar shading channel.
the bilinear interpolation technique

![demosaicing](/digital_camera/docs/assets/images/demosaicing.png)
![demosaicing](/digital_camera/docs/assets/images/demosaicing_1.png)
