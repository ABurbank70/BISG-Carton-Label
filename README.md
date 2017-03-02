# BISG-Carton-Label
Generate a BISG compliant Carton Product label for Publishers

Requires: 
 Perl, Perl-Tk (not Tkx), PDF::Reuse, PDF::Reuse::Barcode (and indirectly Barcode::Code128), and some paitence.
 
Notes:
 One version is the GUI kind (using Tk) for single labels.  It's based on the BISG standard 4x6 Carton Label that many distributors require.  This may contain specific parts for a certain Distribution house and require adjustment for other use.
 
This generates a single page PDF with two 4x6 carton labels.  The barcodes are Code128 C (except for Price, it has a letter in it) and include a 'FNC1' character.
