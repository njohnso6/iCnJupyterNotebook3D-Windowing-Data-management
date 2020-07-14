

<b> Team Members </b>

Ben Busby

Nicholas Johnson

Francesco Tabaro

David Enoma

Jiyao Wang

Guangfeng Song

Yuchen Ge

## Purpose:
#### Purpose of iCn3Dpy Additions for Jupyter Notebooks:
Jupyter Notebooks have become very popular not only for literate programming, but also for creating tidy pairs of code and figures while creating scientific publications. The edits here allow iCn3D to be embedded directly in Jupyter notebooks fully featured, including all windowing, and also allowing the scripting of the figures and visualizations from the code. Creating this functionality can lead to easily reproducible figures. 

The improvements made during this hackathon make this possibile.

#### Windowing Data management:

As iCn3D grows in functionality, it inevitably grows in complexity.  It is imperative that we think about issues on usability.  For example, we now can generate many windows containing valuable information that can overwhelm non-expert users, or even expert users.  Managing these windows efficiently becomes important, as does managing the data they contain for project management, publication, storage, for second level analysis, etc.

In particular, we can generate windows with molecular interactions represented as 2D networks, Tables, 3D depiction, 1D sequence track windows, for one or two mapped structures.  All these windows are related, synchronized in data.  If 2 structures are mapped they can be seen superimposed in 3D, but also now side by side.  At this stage, we need smart window management especially if we need to synchronize visualization of windows of 1D, 2D, 3D, or Tables Representations.  By the same token, comparing data across structures  will become important.

### Problems Solved
The current preliminary version of iCn3D has several issues. 

1. It works in Chrome, but not Safari, specifically the protein-view function.

2. After “view”, the page asks whether to leave the page. 

3. When refreshing the page, the page keeps refreshing.

4. Document objects in popups not available.

Other New Features in this version:
1. ClinVar annotationn viewing

### Installation
1. To build the full iCn3D software, download from [this](https://github.com/ncbi/icn3d) github repo and follow the instructions.
2. Navigate to the JupyterNotebook folder of this repo and follow the instructions.
3. The less updated version is released [here](https://pypi.org/project/icn3dpy/).

### Testing
You can click the arrow icon on the dialog to minimize or expand the window. The test site is [here](https://www.ncbi.nlm.nih.gov/Structure/icn3d2/full.html?divid=div0&mmdbid=6m0j&command=line+graph+interaction+pairs+%7C+!A+!E+%7C+hbonds,salt+bridge,interactions,halogen,pi-cation,pi-stacking+%7C+false+%7C+threshold+3.8+6+4+3.8+6+6;+show+selection;+add+residue+number+labels%7C%7C%7C%7B%22factor%22:%221.4817%22,%22mouseChange%22:%7B%22x%22:0,%22y%22:0%7D,%22quaternion%22:%7B%22_x%22:%220.036185%22,%22_y%22:%220.49963%22,%22_z%22:%220.078595%22,%22_w%22:%220.86191%22%7D%7D)

### Future Work
1. Move from ES5 to ES6
2. Allow functionality in JupyterLab as well





