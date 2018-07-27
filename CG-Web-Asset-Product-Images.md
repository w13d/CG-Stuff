# Marketing Library Images | CG

## Product Image Web Filename 

### Background
---
It is part of Marketing team day to day project to provide Product Image assets (onwards we will call it image(s) only) for CG Web Team in order to build the CG Web and keep it  updated.

CG Web Team need needs images that could be stored in CDN or web server. Among of the requirement are the images must be coded as short as possible. The shorter, the smaller, the better. As eventually it will be faster during uploading (to the server) and downloading during accessing (to client's browser).

CG Web Team simply only need the Product Image assets (onwards we will call it image(s) only) with very simple coded filename.  
E.g. : `60-0107_202` or `88-0018-0011` or `50-3001_403_4`  

CG Marketing team in the other hand needs to file those images in the form that can be readable by human. As they do maintain the images for whole marketing operational, included advertisement and printed material.  
E.g. : `60-0107_20 Silver_RivieraLime_IMG_1652_F` or `88-0018-0011_Tabac_IMG_5446_D2` or `50-3001-A_Black Lacquer_Convex_F`  

### Requirements
Marketing team only to provide images in a state that human can review. No codes needed as possible. 
While Web team only wants images in the most simple form for web use. No other info attached. 

Basically this filenaming and tagging is not an area that both parts like to handle.  
Marketing loves to handle the images, editing, converting, animate it, but not renaming files for web team. 
Web team feels that web development already complicated enough. Renaming files only add more complication on it

To bridge this matter, last time we come to an agreement that :  
Marketing team will provide the images in the most basic form of filename, and human-readable.  
Web team will handle to convert the images filenames into the form as per needed for web-use themselves.

E.g. :
From original images filename provided from factory  
```
     60-0002-0041_JC_JC-Rattan_MorelliJasmine_IMG_0510_D1  
     60-0493-0003_Coco_20Silver-Rattan_Giorgio Crimson_IMG_8369_F  
```
Marketing team will simplify for web team   
```
     60-0002_JC_JC-Rattan_D1  
     60-0493_CC_20S-Rattan_F  
```
Web team to convert it as per they need
```
     /detail1/60-0002_598_7  
     /front/60-0493_308_5  
```

### Challenges 

  * CG finishing and materials increased from time to time.  
    Introduction of new finish will need new tagging for images.
  * Selectable Option for product reviewed from time to time.  
    When a product given new option to be customized will change the tagging images.
  * Not possible to standardize filenaming on Production level/Factory
    Design/Marketing is using normal human sense to read filename. 
    E.g. Renaissance Gold vs Ren.Gold vs R.Gold vs Renaissance G.   
    _(plus any other countless possibilities of typos commonly happens)_  
    will still recognizable as same Renaissance Gold Finish. 

### Solution

### Standard Image Filename for Marketing and Web Team



