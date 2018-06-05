https://www.iscb.org/cms_addon/conferences/ismb2014/posterlist.php?cat=B

ISMB 2014 Poster - B25

**Assessing and Improving In-House Genome and Transcriptome Assembly Solutions: A Case Study**

Jeffrey Cullis, Agriculture and Agri-Food Canada, Canada
Christopher Lewis, Agriculture and Agri-Food Canada, Canada
Iyad Kandalaft, Agriculture and Agri-Food Canada, Canada
Zaky Adam, Agriculture and Agri-Food Canada, Canada
 
Short Abstract: At AAFC, we have developed systems and tools to perform computationally intensive analysis such as genome and transcriptome assembly in an automated, reproducible fashion for researchers working on many target organisms within the organization.

The bioinformatics landscape can change quickly, and incorporation of new tools and best practices is necessary in order to be sure of providing outputs of the highest possible quality. At the same time, there is a lot of useful and often hard-won knowledge embedded in existing systems that should be preserved where it is most beneficial. Here we present an assessment of the advantages and disadvantages of our current system, and propose new directions for development moving forward.

Key aspects of the system to be preserved include the central design goal of a release structure whereby a metadata file providing all sequencing metadata, processing steps, and input and assembly quality statistics are provided along with the final processed outputs. Other useful features include optimization for our specific cluster computing environment, and full automation of steps from raw data acquisition to assembly quality assessment and comparison, to release generation.

A key outcome of our assessment is that greater integration with the Galaxy suite will be necessary moving forward. This would confer a number of advantages, including allowing others to modify and run the pipeline without using the CLI, simplifying and possibly eliminating development overhead for metadata recording, and a more robust ability to extend and interchange tools used in assembly.