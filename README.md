This is the README for the NEURON code used to generate the results in the paper: Mushtaq et. al, Differential thalamocortical interactions in slow and fast spindle generation: A computational model, PLOS ONE, 2022.
Important Note: (The model was developed in NEURON 7.6 version on MacOS).
The Some of the implementation was taken from Thalamocortical and Thalamic Reticular Network (Destexhe et al 1996, ModelDB Acession:3343)..
The code can be run in the NEURON simulation environment, which can be found at https://www.neuron.yale.edu/neuron/ If you need more help than provided below, please consult this web page:
https://senselab.med.yale.edu/ModelDB/NEURON_DwnldGuide.cshtml
To recreate figures from figure 2 of the Knox paper, do the following:
1) download and extract the zip file.
2) use mknrndll (windows) or nrnivmodl (unix and mac) to compile the mod files.
3) Open rundemo.hoc in NEURON and click "Cell and LFP," then click init and run to run the simulation.
![image](https://user-images.githubusercontent.com/117586952/200290915-d3281b68-3261-4e12-b0ff-1d692cfd5c5e.png)
