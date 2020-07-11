# iCn3D in Jupyter Notebook, Windowing Data management, Reference numbering and Mapping 

<b>iCn3D in Jupyter Notebook</b>: 

Jupyter Notebook is a convenient way to do data analysis. It will be great if iCn3D can be embedded in Jupyter Notebook with all features. The current preliminary version of icn3dpy has several limits. It works in Chrome, but has some problemsin Safari. The Jquery dialogs don't show up. It will be good to separate iCn3D dialogs such as "Sequences & Annotations" from the 3D view.

<b>Windowing Data management</b>: 

As the program grows in functionality, it inevitably grows in complexity.  It is imperative that we think about issues on usability.  For example we now can generate many windows containing valuable information that can overwhelm non expert users, or even expert users.  Managing these windows efficiently becomes important, as is managing the data they contain for project management, publication, storage, for second level analysis, etc.   A group reflecting on usability, complexity, prototyping new user interface functions or improving them, such as multi windowing, project and data management, etc. is welcome to come forward for a hackathon project …  

In particular, we can generate windows with molecular interactions represented as 2D networks, Tables, 3D depiction, 1D sequence track windows, for one or two mapped structures.  All these windows are related, synchronized in data.  If 2 structures are mapped, they can be seen in 3D as superimposed, but also now side by side.  At this stage, we need smart window management especially if we need to synchronize visualization of windows of 1D 2D 3D or Tables Representations.  By the same token, comparing data across structures  will become important.

<b>Reference numbering and Mapping</b>: 

On Reference numbering see preprint.  We can establish mapping between structures (based on an alignment) this creates a mapping so one can in principle decide on using a numbering for all aligned sequences/structures and keep track of mapped numbers.  Example Y453 SARS COV 1 (PDB/Refseq) is Y440 in SARS COV 2 … we can decide on a sequence as a reference for its numbering, sounds simple, but not used much.   In the case of Immunoglobulins that exists.  In GPCRs as well, although quite special.  Keeping track of number mappings should be done by the computer, not the scientist  
