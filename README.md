# optimade-scripts

A set of simple shell scripts to query various databases using the
OPTIMADE interface. Essentially a shell-based OPTIMADE client.

The 'optimade-query' script fetches structures from the
OPTIMADE-supporting databases using the OPTIMADE [1,2] interface.

The script accepts any OPTIMADE Filter expression as an argument.

USAGE:
   optimade-query 'elements+HAS+ALL+"Mg","O"+AND+nelements=2'

Refs.:

 1. OPTIMADE intreface specification (2022)
    URL: https://github.com/Materials-Consortia/OPTIMADE
    [accessed: 2022-05-30T10:14+03:00]

 2. Andersen, Casper W. et al. OPTIMADE, an API for exchanging
    materials data (2021) Scientific Data , Vol. 8, No. 1 Springer
    Science and Business Media LLC p. 1-10, DOI:
    https://doi.org/10.1038/s41597-021-00974-z

