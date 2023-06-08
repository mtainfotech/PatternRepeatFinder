# PatternRepeatFinder
Download the software:
    
    Weblink: https://github.com/mtainfotech/PatternRepeatFinder
	click on code dropdown ---> Download Zip   
  
	Downloaded Directory: PatternRepeatFinder (it has four files)
  	    1. PatternRepeatAnnotator.exe (click to run software)
  	    2. PatternRepeatAnnotator.exe.config (chage the output path)
  	    	Default Output Path: C:\PatRepeatFinderResults\<SeqFileName>.csv 
  	    3. README.md. (instructtions to run)
  	    4. log4net.dll (supporting file)
        
INPUT

	1. The **RefSeq Reference Genome Annotation** latest version in ggf format can be downloaded from NCBI website or click at following link:
	https://www.ncbi.nlm.nih.gov/genome/guide/human/ 
	CAUTION! Download human genome in **gff format only**.

	The **chromosome wise sequence data in fasta format** can be downloaded from https://www.ncbi.nlm.nih.gov/genome/?term=human+genome
	Download Chromosome wise human genome files and put into the directory and rename each sequence file with header chromosome number of fasta sequence file
	e.g. Human_genome/NC_000001.fasta        
		          NC_000002.fasta
	CAUTION! Chromosome sequences in fasta format only are acceptable.

	The results will be automatically saved chromosome wise at following location:
		C:\PatRepeatFinderResults\<SeqFileName>.csv
	Result file will be in .csv format which can be opened into any suitable software.

OUTPUT

	GeneId	  GeneSymbol	Strand	Annotation	Start	    End	      Length	Sequence

	107987295 ASMER1        -	Intron	        14857393    14857407  15	GAAGAAGAAGAAGAA

		  Genomic	                        15075771    15075785  15	GAAGAAGAAGAAGAA

	5651	  TMPRSS15	-	Intron	        18445730    18445744  15	GAAGAAGAAGAAGAA
	
If any sequence pattern of user-defined criteria is not found in the genome sequence file. Output file will not be generated. 
