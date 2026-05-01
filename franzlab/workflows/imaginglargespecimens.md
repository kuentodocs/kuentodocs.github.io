---
layout: default
title: Imaging Large Specimens
parent: Workflows
has_children: false
nav_order: 4
---


# **Imaging Large Specimens**
{: .no_toc }

Imaging workflows for moths, butterflies and other large specimens. Specimens should be **digitized** before imaging. **Please image one specimen at the time, as the workflow requires removing the labels.**  
{: .fs-5 .fw-300 }

---

|<img width="6240" height="4160" alt="001652866_dorsal" src="https://github.com/user-attachments/assets/80f016ed-0235-42d0-a290-7882b5aab1ee" />|

----
## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

----

## **Prepare the specimen for imaging**
1. Remove labels carefully **using forceps**. Not necessary if labels not visible.
2. Place the labels, in order, on the pinning block.
3. Place the specimen carefully on a piece of gray clay and position it under a microscope.
4. Remove debris using a fine brush **if necessary**.

## **Prepare the equipment for imaging**
1. Turn on the **computer, mouse and keyboard **(make sure the mouse and keyboard are charged).
2. **Login** to the computer (User: Photographer, no password).
3. Check the Wi-Fi connection. **Login to the KUGUEST** if necessary.
4. Turn on the **camera, flash control** (attached to the camera, if batteries are empty please change them), and **flashes**.
5. Turn on the **stacking system** (push the button on the left side).

|![ImagingSystem](https://github.com/user-attachments/assets/a92fc42a-acca-4dc2-a648-248a69281a97)|


## **Prepare the software for imaging**

### Open EOS 6D Software
**1-** Make sure the camera is on (or turn it off and on again to activate the options).
**2-** Click on **Remote Shooting** to open the menu.

|<img width="593" height="687" alt="eosmenu" src="https://github.com/user-attachments/assets/f793abe0-452a-4539-b8a9-38599579dd75" />|

**3-** Click on the **folder icon** to choose target folder (create one with your name on the Desktop).
<img width="1216" height="897" alt="eosmenufolder" src="https://github.com/user-attachments/assets/75bfd7a1-a4b1-4379-b81c-c9308e79deb6" />

|**To get consecutive file names, customize them as "Prefix+Number" (e.g. IMG_000001).**|

|<img width="1248" height="912" alt="eosmenufolderconfig" src="https://github.com/user-attachments/assets/d5f5c76f-3152-4e69-9366-71f7cf37d64d" />|

**4-** If you don't chose a folder, your images will be saved in **Users>photographer>Pictures>2000**.
**5-** **_Make sure the 100mm lens is attached to the camera. If you need to change lens, please do it carefully or ask for help._**
**6-** Select **Live View Shoot** (make sure the lens cap is off).
**7-** In the Live View window, click **ON** for **Depth-of-field** preview. **_This option will not be available if the flash controller is out of batteries._**
**8-** If necessary, turn on the left flash and place the specimen under the camera. Large specimens will need several takes to image the full body. 

|<img width="7831" height="5027" alt="imagelarge" src="https://github.com/user-attachments/assets/fbd34c5c-d380-4ff9-af63-0196e6aa4c59" />|
|:--:|
|Image each section individually, following the next steps in Zerene.|

### Open Zerene Software
![Zerene](https://github.com/user-attachments/assets/836f6c38-be7a-4d95-b1d3-4ae507c5e214)

**1-**  To select the area to be imaged: **Top Menu > Tools > Stack Shot** to open the Controller. 

|<img src="https://github.com/user-attachments/assets/1f7b5689-0357-469c-bc3f-98f6b524cf84" alt="EOS" width="300">|

**2-**  Click on **Fwd** (Forward, down) to find the lowest point of the specimen and **Set End**.
**3-**  Click on **Back** (up) to find the highest point of the specimen and **Set Start**.
**4-**  Increase or decrease the **Step Size** to get around 20 steps for lateral view and 15 for dorsal view.
**5-**  Change the intensity of flashes if necessary (5-5.5 for 3x-5x magnification, 2-4 for 1x-3x magnification, just try what looks best).
**6-**  On the **upper right corner of EOS 6D**, click on the round button to get a sample image.
**7-**  If lighting and everything	else looks good, turn of the light and go back to the Zerene controller. Click on **Shoot Stack** to get the images.
**8-**  The files will be saved in the folder you selected before. 

## **Focus stack the images in Zerene**
**1-**  To add the images to stack: **Top menu > Files > Add File**.
**2-**  To stack the images: **Top menu > Stack > Align & Stack All (PMax)**.
**3-**  To save the stacked image: **Top menu > File > Save Output Image**.
**4-**  Save the file in **TIFF format**, 16 bits RGB, compression type _none_.
**5-**  Find the folder where you want to save the image and name it using the **catalog number, view, and take number (e.g. 000123456_dorsal_1)**.
**6-**  Click OK.
**7-**  Close the project on Zerene **Top Menu > File > Close Project**.
**8-**  Once you have all your stacked images for the specimen, go to Photoshop. 

## **Align and blend multiple images in Photoshop**
**1-**  Go to **Top Menu > File > Scripts > Load Files into Stack** and select all the files for the specimen.
   
|<img width="1603" height="1504" alt="loadimages" src="https://github.com/user-attachments/assets/d24bf32d-4979-4550-9f89-e4f42b59d38d" />|

**2-**  Once open, select all the layers and go to **Top Menu > Edit > Auto-Align Layers > Collage** to aligne them.
   
| <img width="6016" height="2992" alt="alignlayers" src="https://github.com/user-attachments/assets/d1399762-9bc1-4545-8e19-dfd5b11e5348" /> |

**3-**  Once the layers are aligned, go to **Top Menu > Edit > Auto-Blend Layers > Stack** to stack them.
   
<img width="6016" height="3232" alt="blendlayers" src="https://github.com/user-attachments/assets/a2c591fa-45a3-41b1-97e2-02728849e3dc" />

**4-**  A final image will be produced. The background will be autogenerated if it's uniform enoug.

| <img width="6016" height="3264" alt="finalimage" src="https://github.com/user-attachments/assets/076414e6-1006-4a15-a2d9-236197cbd6aa" /> |

## **Add a Scale Bar in Photoshop**
**1-**  Take an additional (partial) image with a known scale to use it as reference and follow the next steps.
**2-**  Open the output image (TIFF file).
**3-**  Go to **Top Menu > Image> Analysis > Set Measurement Scale** and select the appropriate scale depending on the magnification used.
**4-**  Go to **Top Menu> Image > Analysis> Place Scale Marker** to add the scale bar (1 mm, 2 mm, 5 mm, depending on the size).
**5-**  Save the TIFF file with the scale bar (**Save**, _not Save as_, to keep the same name).
**6-**  Edit later to add logo and caption. Template [here](https://kansas-my.sharepoint.com/:i:/g/personal/k261o393_home_ku_edu/IQDQ-x-0F5HVRorSwx6rDZJJAXhECCci2ziyzWaXz3eFySs?e=Vvd9ah).

|<img width="6240" height="4160" alt="001652866_dorsal" src="https://github.com/user-attachments/assets/de0f82b3-1570-413b-9812-b729fb49c4e8" />|
|:--:|
|Edited image, dorsal view.|

## Prepare the specimen for next image, repeat all steps

## Prepare the specimen to return it 
**1-**  Pin the labels back (locality, barcode) **using a pinning block**.
**2-**  Add a “Photo taken” green label.
3. Genitalia vials and determination labels should be pinned below the photo label.
4. Return the specimen to its unit tray and drawer.
