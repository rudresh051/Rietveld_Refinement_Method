# Rietveld Refinement

example - https://www.researchgate.net/figure/Color-onlinea-Rietveld-refinement-of-the-X-ray-diffraction-pattern-of-CeIr3-The-data_fig1_338547078

![alt text](image.png)

Y = mx + c  
it's very simple to solve

> You have peak width, peak height and peak position.  
> So basically refinement mean that you are going to continuously change the values and  
> ultimately changing the black color graph  
> We need to superimpose onto this experimental graph  

> We have 3 mathematical function  
> Gaussiaon, Laurentizian, Pseudo-Voight functions are used to do the refienement of XRD Pattern  
> In Rietveld refinement, the crystallographic based parameters - u,v,w, background, FWHM.  
> So you essentially have to change the values of those such that calculated plot will have a perfect overlap onto the experimental  
> That is your only objective. Not going to be an easy task.  
> We will practise some examples and it will become clear  

## Rietveld Refinement Steps

1. Step 1 - Convert experimental data into .dat file
   1. Only single row with step size

![alt text](image-75.png)

![alt text](image-76.png)

2. Step 2 - Obtain the best available reference file. we have already provided you.
3. Step 3 - Convert .cif file into pcr file  where fullprof will store all the required information and result corresponding to the refinment.

![alt text](image-1.png)

click "ok" and these buttons will be enabled  

![alt text](image-2.png)

Click on "Save" icon and .pcr file will be generated  

![alt text](image-3.png)

* Give title - Click on general

![alt text](image-86.png)

> This is the utmost important file because all the calculation steps, parameter results will be store in this PCR file itself  

* click on Patterns option and and below will open and click on data file peak shape.

![alt text](image-87.png)

Select File

![alt text](image-4.png)    

* Refinement/Solution  

![alt text](image-5.png)

* Select Pseduo-Voight

![alt text](image-6.png)

change the theta range 

![alt text](image-7.png)

click ok and ok

now change refinement 

![alt text](image-8.png)

click on save again and that would save whatever changes you would have done.  

Click on Run FullProf Program and you will get graph like this 

![alt text](image-9.png)

* Red - Black to get the blue
* Our objective should be that Blue line should be straight line after refinement


* Example

![alt text](image-77.png)

for above peaks are broad. so we need to reduce our step size. you have to do the Background removal or smoothening.