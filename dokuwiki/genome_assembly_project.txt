===== Genome Assembly Pipeline =====

=== Project Introduction ===
From April-September 2013, I developed a pipeline in Perl that managed and processed raw DNA and RNA sequencing data from initial QC and trimming stages, through to genome and transcriptome assembly and quality assessment, to final data release. Key goals included metadata management and implementation of a formal release process. This allowed metadata about sequencing parameters, data processing tools and tool versions applied, and final assembly quality statistics to be included with the release to ensure reproducibility of results. This pipeline was used to create initial genome assemblies for over 55 organisms, and transcriptomes for over 25 organisms, many of which were novel species/strains.

=== Publications ===
This work was presented at ISMB 2014 in Boston, MA.

{{ismb_2014_poster_b25_jc.png}}

{{:ismb_2014_poster_b25_jc.pdf|PDF}} | {{:ismb_2014_poster_b25_jc.pptx|PPTX}} 

Li X, Yuan K, Cullis J, Lévesque CA, Chen W, Lewis CT, De Boer SH. 2015. [[http://genomea.asm.org/content/3/2/e00240-15.full|Draft genome sequences for Canadian isolates of Pectobacterium carotovorum subsp. brasiliense with weak virulence on potato.]] Genome Announcements 3(2):e00240-15. doi:10.1128/genomeA.00240-15.

=== Github ===

Code is available at: https://github.com/AAFC-MBB/crti-assembly-pipeline
  git clone https://github.com/AAFC-MBB/crti-assembly-pipeline.git

{{tag>Perl bash SGE genomics}}