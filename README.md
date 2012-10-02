create_psf(1)
==========

script for creating a psf given a protein and rtf

## SYNOPSIS
	create_psf pdb_file rtf_file out_psf_file

## DESCRIPTION
`create_psf` create CHARMM formatted psf files from pdb files. The residues in the 
pdb file must have all atoms present. That is, the assumption is that you have used
a program such as [PDB2PQR](http://www.poissonboltzmann.org/pdb2pqr/) to add missing
atoms prior to use of this program. Additionally, it assumes all atoms and uniquely
numbered and residues have unique number+insertion code.

## AUTHOR
David Hall <david@acpharis.com>

## NOTES
Contributions that break CentOS 5 support will not be accepted
