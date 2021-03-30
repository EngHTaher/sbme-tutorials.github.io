---
layout: presentation
style: laminal
highlighter: monokai
course: "sbe404"
category: "presentation"
year: "2019"
title: "Week 3: Images in Frequency Domain"
by: "Ayman Anwar"
author: "Eslam Adel "
---


<textarea id="source">

class: center, middle
##  Images in Frequency Domain

Prepared by: Eslam Adel 

Instructed by: Ayman Anwar

email: ayman.anwar.bio@gmail.com

---
class: left, top
### 2D Discrete Fourier Transform 

--
For Image I(x,y) DFT is I(u,v) where

--

<img style="width:100%" src="../../images/DFT.png">
---
class: left, top
### Basis Functions

--
<img style="width:60%" src="../../images/Basis_functions.png">


---

class: left, top
#### Example

--
<img style="scale:100%" src="../../images/Original_Image.png">

---
class: left, top
#### Example Cont'd

--
<img style="scale:100%" src="../../images/Fourier_Spectrum_of_the_image.png">

---

class: left, top
### Numerical Example

Consider Image f(x,y) Shown 

<img style="width:60%" src="../../images/FT_ex.png">

find 

F(0,0), F(0,1) and F(1,0)

---

class: left, top
### Properties of FT

--
Complex ( Magnitude and Phase) 

--

Dynamic Range Compression 
--
<img style="scale:80%" src="../../images/DRC.png">

---
class: left, top
### Properties of FT Cont'd

Fourier transform of the image is symmetric
--

Application MRI Half Fourier Imaging
--  

<img style="scale:80%" src="../../images/HFI.png">
--

Where redundancy comes from ??

---

class: left, top
### Properties of FT Cont'd

--

 DFT is periodic



 Discretization implies periodicity
 --

 No one to one corresponding
 $$I(u,v) = T(I)(x,y)$$ not $$T(I(x,y))$$ 
---


class: left, top
#### Inverse Fourier Transform
<img style="width:100%" src="../../images/IFT.png">

---

class: left, top
#### Fourier Filtering
<img style="width:100%" src="../../images/Fourier_Filtering.png">

---


class: left, top
#### Color Image Processing
<img style="width:100%" src="../../images/block_diagram.png">


---


class: left, top
#### Point Operator

Point Processor (Each individual Point)

Example : Thresholding

--

<img style="width:100%" src="../../images/Threshold.png">

---

class: left, top 
### Point Operator Cont'd
Negative Image
<img style="width:80%" src="../../images/negatve.png">

---

class: left, top 
### Histogram Equalization

Enhance Contrast of the image

<img style="width:100%" src="../../images/equalization.png">

---


class: left, top 
### Histogram Equalization Example

Consider a 64 × 64 image with 7 gray levels( 0 1 2 3 4 5 6 ).

The histogram of this image is given by:


--
<img style="width:30%" src="../../images/histEx.png">

Apply Histogram Equalization
---


</textarea>