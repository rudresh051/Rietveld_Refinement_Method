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
> So you essentially have to change the values of those such that calculated plot will have a perfuct overlap onto the experimental  
> That is your only objective. Not going to be an easy task.  
> We will practise some examples and it will become clear  

1. Step 1 - Convert experimental data into .dat file
2. Step 2 - Obtain the best available reference file
3. Step 3 - Convert .cif file into pcr file  

![alt text](image-1.png)

click "ok" and these buttons will be enabled  

![alt text](image-2.png)

Click on "Save" icon and .pcr file will be generated  

![alt text](image-3.png)

> This is the utmost important file because all the calculation steps, parameter results will be store in this PCR file itself  

* Select File

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