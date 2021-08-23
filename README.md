# bioinformatics-one-liner
Will try to put here all the one liners I come across


* Finding a gene name across multiple files
Let's assume I want to find a gene, called **Foxp1** in the 2nd column in in a range of *.csv files. In the Terminal, run this:<br/>
`cut -d, -f 2 *.csv | grep -c 'Foxp1'`<br/>
It will output an integar, showing how many times **Foxp1** is found in those files. 
