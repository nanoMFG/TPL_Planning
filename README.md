# nanoMFG Software Planning Document
<!-- Replace text below with long title of project:short-name -->
## The Coolest nanoHUB Tool: Two Photon Lithography Analysis
### Target Release: 12.15.2021 

## Development Team
<!-- Complete table for all team members 
 roles: lead, developer, reviewer
 status: active, inactive
-->
Name | Role | github user | nanohub user | email | status
---|---|---|---|---|---
Yuhang Yang | developer| yang221 | yang221 | yang221@illinois.edu | active
Sixian Jia | developer | sixianj2 | sixianj2| sixianj2@illinois.edu | active



## 1. Introduction
Data Based Uncertainty Quatification and Process Capability Analysis for Two Photon Lithography

### 1.1 Purpose and Vision Statement
<!-- Why are we building this tool?
What is the key benefit
How does it relate to existing tools and existing software?
How does it fit into the overall objectives for the nano **manufacturing** node?
Who will use this software?
-->
To improve the utility and ultimate dissemination of our published TPL software tool, we have been developing a framework for which to incorporate (experimental) process variability in our simulation model in order to obtain insight on the repeatability of the TPL process. Our initial approach uses 3D geometric measurements of fabricated structures/features.The tool will provide:

1.Spatial distributions of geometric features.
(a)Height
(b)Radius
(c)Volume

2.Geometric deviation from the designed shape.

3.Summary of geimetric features and errors

### 1.2 References
<!--List any documents or background material that are relevant.  Links are useful. For instance, a link to a wiki or readme page in the project repository, or link to a uploaded file (doc, pdf, ppt, etc.).-->
 [1] Cumpston, Brian H., Sundaravel P. Ananthavel, Stephen Barlow, Daniel L. Dyer, Jeffrey E.
 Ehrlich, Lael L. Erskine, Ahmed A. Heikal et al. "Two-photon polymerization initiators for three-
 dimensional optical data storage and microfabrication." Nature 398, no. 6722 (1999): 51.
A47

 [2] Juodkazis, Saulius, Vygantas Mizeikis, Kock Khuen Seet, Masafumi Miwa, and Hiroaki Misawa.
 "Two-photon lithography of nanorods in SU-8 photoresist." Nanotechnology 16, no. 6 (2005): 846.
 
 [3] Tormen, Microelectron, L. Businaro, M. Altissimo, F. Romanato, S. Cabrini, F. Perennes, R.
 Proietti, Hong-Bo Sun, Satoshi Kawata, and E. Di Fabrizio. "3D patterning by means of
 nanoimprinting, X-ray and two-photon lithography." Microelectronic Engineering 73 (2004): 535-
 541.
 
 [4] Jhaveri, Shalin J., Jesse D. McMullen, Rint Sijbesma, Loon-Seng Tan, Warren Zipfel, and
 Christopher K. Ober. "Direct three-dimensional microfabrication of hydrogels via two-photon
 lithography in aqueous solution." Chemistry of materials 21, no. 10 (2009): 2003-2006.

[5] Montgomery, Douglas C. Statistical quality control. Vol. 7. New York: Wiley, 2009.
 
 [6] Chen, K. S., M. L. Huang, and R. K. Li. "Process capability analysis for an entire
 product." International Journal of Production Research 39, no. 17 (2001): 4077-4087.
 
 [7] Wu, CF Jeff, and Michael S. Hamada. Experiments: planning, analysis, and optimization. Vol. 552.
 
## 2 Overview and Major Planned Features
<!--Provide and overview characterising this proposed release.  Describe how users will interact with each proposed feature. Include a schematic/diagram to illustrate an overview of proposed software and achitecture componets for the project-->

### 2.1 Product Background and Strategic Fit
<!--Provide context for the proposed product.  Is this a completely new projects, or next version of an existing project? This can include a description of any contextual research, or the status of any existing prototype application.  If this SPD describes a component, describe its relationship to larger system. Can include diagrams.-->
TPL Mechanism

![Screen Shot 2020-11-10 at 1 24 10 AM](https://user-images.githubusercontent.com/71730024/98636077-1c792c80-22f4-11eb-89ce-608cf636f7ae.png)

Hardware Setup

![Screen Shot 2020-11-10 at 1 27 22 AM](https://user-images.githubusercontent.com/71730024/98635993-edfb5180-22f3-11eb-8c51-5b5ef39ac003.png)


### 2.2 Scope and Limitations for Current Release
<!--List the all planned goals/features for this release.  These should be links to issues.  Add a new subsection for each release.  Equally important, document feature you explicity are not doing at this time-->

In the current release, the tool is used to simulate the final shape of a CAD design geometry. For next version, the tool will use 3D geometric measurements to fabricate structures and features.

##### 2.2.1 Planned Features

1.Spatial distributions of geometric features
(a)Height
(b)Radius
(c)Volume

2.Geometric deviation from the designed shape

3.Summary of geimetric features and errors
### Current Progress
1.Spatial distributions of geometric features
![Screen Shot 2020-11-10 at 1 44 17 AM](https://user-images.githubusercontent.com/71730024/98637749-dd000f80-22f6-11eb-841b-a9ff00635cdf.png)

![Screen Shot 2020-11-10 at 1 44 24 AM](https://user-images.githubusercontent.com/71730024/98637753-dec9d300-22f6-11eb-869a-60c69e5ea4c1.png)

![Screen Shot 2020-11-10 at 1 44 30 AM](https://user-images.githubusercontent.com/71730024/98637758-e0939680-22f6-11eb-9a35-5833cc8a0ae6.png)

2.Geometric deviation from the designed shape

![Screen Shot 2020-11-10 at 1 45 03 AM](https://user-images.githubusercontent.com/71730024/98637761-e25d5a00-22f6-11eb-9078-1fe54cc099b7.png)

3.Summary of geimetric features and errors

![Screen Shot 2020-11-10 at 1 45 14 AM](https://user-images.githubusercontent.com/71730024/98637765-e38e8700-22f6-11eb-872a-c4c8ae830840.png)

### 2.3 Scope and Limitations for Subsequent Releases
<!--Short summary of  future envisioned roadmap for subsequent efforts.-->


### 2.3 Operating Environment
<!--Describe the target environment.  Identify components or application that are needed.  Describe technical infrastructure need to support the application.-->

The TPL Analysis tool uses Jupyter Notebook to run. Users can use the tool from Nanohub website or download the code from NanoMFG.

# 3. User Interaction and Design  

### 3.1 Classes of Users


### 3.2 User Requirements



### 3.3 Proposed User Interface



### 3.4 Documentation Plan



### 3.5 User Outreach Plans



## 4. Data and Quality Attributes 
