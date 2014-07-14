# ENT - A Pseudorandom Number Sequence Test Program

ent applies various tests to sequences of bytes stored in files and reports the results of those tests.

The program is useful for evaluating pseudorandom number generators for encryption and statistical sampling applications, compression algorithms, and other applications where the information density of a file is of interest.

This is a fork of the upstream code and modifies the terse output to include probability information and condense output.

## Usage
See http://www.fourmilab.ch/random/ for more information.

### Terse Mode Ouput
In order to allow for sequential testing using the same output file, terse mode no longer prints a header row.  Additionally Chi Squared probability has been added to the ouput.

The columns are as follows:

`Count,Entropy,Chi-square,Chi-probability,Mean,Monte-Carlo-Pi,Serial-Correlation`

## Author 
John Walker, http://www.fourmilab.ch
Contribution by Colin Woodcock, http://www.netsrv-consulting.com

## License
This software is in the public domain.
Permission to use, copy, modify, and distribute this software and its documentation for any purpose and without fee is hereby granted, without any conditions or restrictions.
This software is provided “as is” without express or implied warranty.
