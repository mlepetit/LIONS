# LIONS ERROR CODES

### Error 1 - internal software error. Check last-run software.

## Intiailzation Codes ---------------------------
### Error 2 - Initializal file missing or inaccesible
	A file is missing. Ensure you have a complete version of LIONS and/or
make the missing script readable/exectable

### Error 3 - A LIONS script is missing
	A script is missing from ./LIONS/scripts/ ; ensure your copy of LIONS is
complete or redownload.

### Error 4 - Initialization bin missing
	A binary is not found on the system. Configure 
./LIONS/bin/intializeBin.sh for your system

### Error 5 - A resource file is missing or unreadable
	Checking/initialization of ./LIONS/scripts

### Error 6 - A python requisite is missing.

### Error 7 - The input read file (.bam or .fastq) is non-readable or empty
	7A - Bam file error
	7B - FastQ file error. Ensure the two files are comma seperated in the input

## eastLion Codes --------------------------------

### Error 10 - alignment not generated
	An attempt was made to generate an alignment but the output file was
empty at the end of the script

### Error 12 - wig not generated
	An attempt was made to generate the wig file but the output file wasn't
there after the script ran

## westLion Codes -----------------------------------

### Error 15 - A lions file wasn't generated
	In the run, one of the lions files wasn't generated which means there
was an error. Don't run West Lions pipeline.
