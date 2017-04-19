# Survo-help
Survo help repository includes all the necessary files to create [Survo help web page](https://d3l3g8x9oq84ue.cloudfront.net/). 

## How to participate
**Make preparations**
* Make a username for Git at www.github.com.
* Ask from [Jouni](https://github.com/JouniVatanen) to participate at jounipvatanen at gmail.com.
* Download and install Git e.g. http://git.scm.com/downloads.
* Start Git and update your basic info in the command line. [For more info about Git](git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup).
```
git -config --global user.name "John Doe"
git -config --global user.mail johndoe@example.com
```

**Use Git the easy way**
* Start Git and go to your working directory in the command line where you want Survo-help folder to be saved.
* Download a copy of the files to your working directory.
```
git clone https://github.com/JouniVatanen/Survo-help
```
* Make changes to an EDT-file you choose using Survo.
* Upload the file to a server.
```
git add <filename>
git commit -m "Commit message”
git push origin master
```
* Insert your github username and password.
* If you do not have all the recent updates then before uploading the file you need to download the newest files 
```
git pull https://github.com/JouniVatanen/Survo-help
```

**Note:** If you have problems to update Git, you can always send the EDT-file to Jouni at jounipvatanen at gmail.com. That way you do not need to download Git. Instead you can download the zip-file from this page.

**How to work with the Survo-help**
1. Install and open [R](https://cran.r-project.org/) and its muste package.
1. Open Survo-help.EDT and activate /ACTIVATE +. This is not necessary, but this way you ensure that all your settings are updated.
1. Tell Jouni jounipvatanen at gmail.com what part you are going to work on.
1. Open EDT-file you want to work on and read its instructions. 
1. Activate the COPY command and you get an empty html template you can start to work on.
1. Go to the html template and first replace XXX by capital command name e.g. FILE SAVE. Replace xxx by lowercase command name and replace possible spaces with - e.g. file-save.

## EDT-files and examples of html-files it creates
* SURVO-HLP // All the settings. Activate this before anything!
* MISC      // frontpage, misc-pages, tutorial, [Jouni](https://github.com/JouniVatanen)
* EXAMPLES  // examples
* EDITOR    // numerical conversions, links, help, navigation, menus,
* ECOMMAND  // SET, COUNT, SORT, FORM, TRANSP, INTERP, C+, C*, C-, C/, C%, L+, L*, L-, MOVE, FIND, REPLACE, VFIND, CLEAR, ...
* SYSTEM    // SAVE, LOAD, REDIM, INIT, RESIZE, CD, DISK, OS, TIME, CODES, WIN, ...
* FILE      // FILE LOAD, FILE SAVE, FILE CREATE, FILE UPDATE, DATA, FILE AGGR, ... [Jouni](https://github.com/JouniVatanen)
* TAB       // TAB, TABFIT, TABTEST, /TABULATE, BURT, MTAB, ...
* MATRIX    // MAT, MATRUN, MAT #TRANSFORM, MAT #MULT, MAT #SAMPLES, POL, TRAN1, POSDIR, DIST, LSCAL, ...
* GRAPH     // PLOT  GPLOT, RPLOT, /BOXPLOT, EPS JOIN, ...
* KEYS      // F-keys, PREFIX, touch, ...
* PRINT     // PRINT
* TEXT      // TXTCONV, TXTRIM, LIST, TRANSPOSE, DATAFIND, LOADP, SAVEP, SHOW, ...
* STAT      // STAT, STATMSF, MINSTAT, HISTO, ...
* MATH      // SIMPLEX, COMB, INTREL, /CONTFRAC, GEOM, MARKOV, touch, editorial computing, library functions,
* METHOD    // GENREG, LINREG, REGDIAG, ESTIMATE, MAHAL, CLASSI, RELIAB, MNSIMUL, FACTA, MATRUN, PFACT, ROTATE, CORRESP, CANON, DISCO, /PCOMPR, /PCOMPCOV, /MNSIMU, /COV, /MTEST-README, /CANCORR, ... [Kimmo](https://github.com/KimmoVehkalahti)
* TRANSFORM // TRANSFORM, CLASSIFY, LINCO, SMOOTH, VARSTAT, VAR, ...
* SUCRO     // sucro, TUTLOAD, TUTSAVE, /ACTIVATE, other sucros, ...
* R         // Connections between R and Survo [Reijo](https://github.com/rsund)
