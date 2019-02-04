# RyanLabUnixBestPractices
A set of conventions we use in our lab

### Directory Names
* We begin directory names with a 2 digit number followed by a dash '-'
* The two digit numbers are incremental based on directories that already exist
** if there are directories starting with `01` and `02` then a new one would start with `03`
* We use all caps for directory names
* We use an underscore to delimit words in directory names
* An example of a directory name: `01-DIATOM_PHYLOGENY`

### Subdirectories
* The outermost directory is usually a project
* Within a project directory would be individual analyses
* All raw data or final assemblies are stored in a subdirectory called `00-DATA`
* Each analysis is given it's own directory starting with 2-digit numbers
** For example, under `01-DIATOM_PHYLOGENY` you might have the following:
*** `00-DATA`, `01-TRINITY`, `02-TRANSDECODER`, `03-ORTHOFINDER`, `04-MAFFT`, `05-IQTREE`, `06-RAXML`

### 00-README files
* Each directory and subdirectory should include a `00-README` file
* These can include a small narrative of what the analysis intends to achieve
* a date, author info, etc.
* Most importantly, it should have the commands that were run to produce the files in that subdirectory (hint: the `history` command is your friend)



