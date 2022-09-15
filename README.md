# BISG-Carton-Label
Generate a BISG compliant Carton Product label for Publishers

Requires: 

 Perl, Perl-Tk (not Tkx), PDF::Reuse, PDF::Reuse::Barcode (and indirectly Barcode::Code128), Spreadsheet::ParseExcel, Switch, and some paitence.
 
Notes:

   Carton_Tk is the GUI version, Carton_xls (and Updated_Carton_xls and Carton_4x6) is the batch conversion script.  If you're doing one label, try the GUI version.  Otherwise, use the Carton_xls_template.xls file to create a batch job.
   
This may contain specific parts for a certain Distribution house and require adjustment for your use.  You should edit both files and change "my $publisher= " to a valid name.
 
This generates a single page PDF with two 4x6 carton labels (hopefully, BISG compliant).  The barcodes are Code128 C (except for Price, it has a letter in it) and include a 'FNC1' character.

You can see the complete specifications here: http://bisg.org/page/Guides

See the wiki for more detailed information https://github.com/ABurbank70/BISG-Carton-Label/wiki
