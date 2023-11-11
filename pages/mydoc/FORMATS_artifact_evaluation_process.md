---
title: "Artifact Evaluation Process"
sidebar: mydoc_sidebar
permalink: FORMATS_artifact_evaluation_process.html
toc: false 
folder: mydoc
---
### PArtifact Evaluation Process
Authors of accepted papers with computational results will be invited to submit an Artifact Evaluation Package (AEP) to be reviewed and evaluated for reproducibility and usability by the Artifact Evaluation (AE) Committee.

The main objectives of the AE initiative are to:

* carry out an independent reproduction of the results stated in the papers and thereby strengthen the quality of the published papers
* find possible errors in the software implementation
* provide feedback on the artifacts’ documentation and reusability
* raise the profile of the FORMATS conference series by recognising the efforts made by authors towards open and reproducible research.
Papers that pass the AE will receive a badge that will appear on the first page of the published version; these papers will also be listed on the conference webpage and the final proceedings as having passed the AE. The AE will also feature a Best Artifact award. Papers that do not pass the AE will simply be treated as papers that did not submit an AEP.

### Submission guidelines
<a href="" target="_blank">EasyChair link for AEP submission</a>

After your paper is accepted for FORMATS 2023, follow the above link to submit your artifact to "FORMATS 2023 AE" on EasyChair. Submit a PDF of the accepted paper, and an abstract that briefly describes (i) the paper and (ii) the relationship between the artifact and the paper. As part of the abstract, (iii) provide a URL to a single zip file containing the AEP. The zip file must be accessible for download by the AE chairs, remain unchanged after submission, and be available for the duration of the AE process. Optionally, (iv) include a SHA-1 hash of the zip file in the abstract to allow AE chairs and committee members to check the integrity of their downloads.

Each AEP must include:

1. a document (pdf or text file) indicating:
    * which specific results of the paper (tables, figures, etc.) are part of the AEP, and 
    * all necessary instructions on how to install and run the software so as to reproduce the specified results. Ideally, authors should provide push-button scripts that will automatically generate figures or tables from the paper.
1. all necessary software and data made available for the entire duration of the AE process in one of several ways (in decreasing order of preference):
    * a virtual machine, e.g., using VirtualBox or VMware
    * a Docker image along with host OS info in the accompanying document
    * source code that does not requires local installation, e.g.,
        * a Code Ocean capsule
        * a shared MATLAB Drive folder that could be run using MATLAB Online for submissions in the MATLAB ecosystem.

If none of the above alternatives is viable, please contact the AE Chairs:(**TBD**)

We strongly encourage authors to arrange for an independent test of their AEPs before the final submission. This could be for example performed by collaborators or colleagues who are not familiar with the artifact in question.

We also suggest authors add a suitable license should their artifact be publicly available. Submission of an artifact implies at least a license allowing AE Committee members to review the artifact for FORMATS 2024.

### Evaluation process
The AE process will be single-blind.

* AEPs will be reviewed by at least three anonymous members of the AE Committee. Reviewers will evaluate AEPs based on the Evaluation Criteria listed below.
* To maintain the single-blind review process, authors must not try to discover the identity of the reviewers and must turn off any kind of analytics in their AEPs.
* AEPs will be treated as confidential material. The AE Committee members will not
  * use the AEPs for any purpose except reviewing for FORMATS 
  * share the AEPs under evaluation
  * store the AEPs after the AE process has concluded
* If the evaluation of an AEP requires a financial cost (e.g., running it on a cloud service), it might not be evaluated.

### Evaluation criteria
Reproducibility and usability are the two main criteria used by the reviewers. Please see <a href="https://www.acm.org/publications/policies/artifact-review-and-badging-current" target="_blank">this ACM page</a>


**Reproducibility** essentially means that the results of the paper have been independently obtained by a team other than the authors using artifacts provided by the authors. Reviewers will assign a score and provide feedback based on:
* how many and to what degree have the results in the paper been reproduced following the instructions supplied by the authors
* how easy it is to reproduce the results of the paper, which includes downloading, installing, and running the AEP
* the quality and the extent of the supplied documentation for using the AEP.

**Usability** overs all aspects of good practices regarding documentation, the software development process and/or certification, and the usage and extension of the software. Reviewers will give a special consideration in their written feedback for packages that include the following nice to haves:
* how well-architected and easy-to-follow the source code is [if provided]
* any additional efforts taken by the authors for ensuring correctness of their implementation of algorithms (e.g., unit tests, statistical analyses, formal verification)

### Example AEP
* Citation: Akshay Rajhans, Srinath Avadhanula, Alongkrit Chutinan, Pieter J. Mosterman, and Fu Zhang, “Graphical Modeling of Hybrid Dynamics with Simulink and Stateflow,” In Proceedings of the 21st ACM International Conference on Hybrid Systems: Computation and Control, 2018. Best Repeatability Evaluation Award Finalist.
* <a href="https://dl.acm.org/doi/10.1145/3178126.3178152" target="_blank">Official version</a>
* <a href="https://arajhans.github.io/files/papers/RajhansAC+_HSCC18.pdf" target="_blank">Author postprint</a>

* AEP files
  * <a href="https://drive.matlab.com/sharing/e7e5bf61-23b4-40d1-aa43-0288e375a74c/" target="_blank">Shared MATLAB Drive folde</a>
  * <a href="https://arajhans.github.io/files/papers/RajhansAC+_HSCC18_RE.pdf​" target="_blank">Accompanying instructions in PDF</a>
    * Note that these instructions were originally intended to work with MATLAB Release R2017b. The code in the MATLAB Drive folder has been slightly modified to directly work with the latest MATLAB release (R2021b at the time of posting this) in MATLAB Online.