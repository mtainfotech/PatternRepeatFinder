# PatternRepeatFinder
Download the software:
    
    Weblink: https://github.com/mtainfotech/PatternRepeatFinder
        
	click on code dropdown ---> Download Zip   
        
	Downloaded Directory: PatternRepeatFinder (it has four files)
            
	    PatternRepeatAnnotator.exe (click to run software)
            
	    PatternRepeatAnnotator.exe.config (chage the output path)
            
	    	C:\PatRepeatFinderResults\<SeqFileName>.csv 
            
	    README.md. (instructtions to run)
            
	    log4net.dll (supporting file)
        
INPUT

The RefSeq Reference Genome Annotation latest version in ggf format can be downloaded from NCBI website or click at following link:

https://www.ncbi.nlm.nih.gov/genome/guide/human/ 

CAUTION!

Download human genome in gff format only.

The chromosome wise data can be downloaded from https://www.ncbi.nlm.nih.gov/genome/?term=human+genome

Download Chromosome wise human genome files and put into the directory and rename each sequence file with header chromosome number of fasta sequence file

	e.g. Human_genome/NC_000001.fasta
        
		NC_000002.fasta

CAUTION!

Chromosome sequences in fasta format only are acceptable.

The results will be automatically saved chromosome wise at following location:

C:\PatRepeatFinderResults\<SeqFileName>.csv

Result file will be in .csv format which can be opened into any suitable software.

Output Format:

GeneId	  GeneSymbol	Strand	Annotation	Start	    End	      Length	Sequence

107987295	ASMER1	    -	      Intron	    14857393	14857407	15	    GAAGAAGAAGAAGAA

                Genomic	                        15075771	15075785	15	    GAAGAAGAAGAAGAA

5651	    TMPRSS15	  -	      Intron	    18445730	18445744	15	    GAAGAAGAAGAAGAA
			    Genomic	                        18535772	18535786	15	    GAAGAAGAAGAAGAA
653214	  PPIAP22	    +	      Intron	    18745147	18745167	21	    GAAGAAGAAGAAGAAGAAGAA
100288151	SREK1IP1P1	+	      Intron	    19500659	19500676	18	    GAAGAAGAAGAAGAAGAA
