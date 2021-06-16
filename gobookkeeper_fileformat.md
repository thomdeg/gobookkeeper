
Example

    ; a comment
    ; an entry consists of a date line and at least two lines with accounting data.
    
    2021-05-21 title or short description
      1800  21.00 H  (credit) more text here
      6825     ++ S  (debit) e.g. accounting infos
   
    ; the letter 'H' stands for credit (German: "Haben")
    ; the letter 'S' stands for debit  (German: "Soll")
    ; the symbol ++  calculates the missing value automatically
    ; (date in ISO-format yyyy-mm-dd)
    
    ; commands:
    !! set year=2021
    !! set number_sep = auto
    !! include "./filename.dat"
    
    
    
   


(inofficial: maybe software should work with  +,-  or  credit/debit, now it uses German symbols S/H as described above)
    
