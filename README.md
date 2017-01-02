Morris A. Swertz
University of Groningen, University Medical Center Groningen, Genomics Coordination Center, Groningen, the Netherlands
University of Groningen, University Medical Center Groningen, Department of Genetics, Groningen, the Netherlands

<h1>NGS_ScRNA</h1>

The sequencer is producing reads (in FastQ format) and are aligned to the hg19 reference genome with STAR (Dobin A et al. <sup>1</sup>).
Dropseq (Macosko EZ et al [3]) was used for flaging individual cells and UMI's. The gene level quantification was performed again by using 
Dropseq filtering readcount on unique UMI's. Picard tools (Picard Sourceforge <sup>2</sup>) is used for sorting, merging or format converting SAM/BAM files.

<h3>References</h3>

1. Dobin A, Davis CA, Gingeras TR: STAR: ultrafast universal RNA-seq aligner. 10.1093 bts635 Bioinformatics (2012)
2. Picard Sourceforge Web site. http://picard.sourceforge.net/ ${picardVersion}
3. Highly Parallel Genome-wide Expression Profiling of Individual Cells Using Nanoliter Droplets
   Macosko EZ et al,Cell, 2015
