# predict-activity-of-short-antimicrobial-peptides













FUNCTIONAL and TECHNICAL REQUIREMENTS DOCUMENT










Title:
predict activity of short antimicrobial peptides

Develop By:   Kashaf Naz





TABLE OF CONTENTS

Obj.	Headings	Page no.
1	General Information 	2
2	 Purpose	2
3	Scope	2
4	Acronyms and/or definitions	2
5	Project Overview	3
6	Functional Requirements and user Impact	3
7	Data Resource	3














1.	General information
predict activity of short antimicrobial peptides.
I will be building a machine learning model to predict antimicrobial peptides
	
1.1.	Purpose
Antimicrobial resistance is an urgent and global health problem as existing drugs are becoming ineffective against the treatment of antimicrobial infections.
1.2.	Scope
Particularly, we will be retrieving 2 datasets consisting of antimicrobial peptides (positive set) and non-antimicrobial peptides (negative set). Then, I will be computing some peptide features to quantitatively describe peptides followed by model building and finally model interpretation where we shed light on the key important features important for predicting antimicrobial peptides.
2.	Acronyms and/or definitions

Conda	In which we install packages like python, Our working Environments
Pfeature	Pfeature allow us to compute properties of Amino Acid which will be crucial to Quantify the Molecular properties of peptides  
Jupyter NoteBook/ Colab	
CD-Hit from bioconda	A library allows us to fit or out any Redundancy in Peptide Sequence, meaning that peptide that are Much Similar will be removed, So We will get non-redundant and a unique sub set of Peptides that will be using in Molecular sequence
Pandas	It’s data-frame for viewing Visualization
Python	For Programing
Random Forest classifier	modeling
Matplotlip	Graph visualization




3.	Project Overview
I will be computing some peptide features to quantitatively describe peptides followed by model building
 Functional Requirements and user Impact

Calculate Features Using P features
Featuring most to least featured amino acid
Data Resource:
A research paper




