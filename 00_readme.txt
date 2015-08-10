link_check is a dir for a shallo evaluation of 
possible smesmn entries via fin.

1. extract all t-elements from smefin/src
2. extract all l-elements from finsmn/inc/2015/
3. sort-uniq each file
4. compare the lists:

link_check>c *_su.txt
   17674 l_fin_su.txt
   10408 t_fin_su.txt
link_check>comm -12 l_fin_su.txt t_fin_su.txt |c
    4908
 ==> let's add about 1100 entries due to possible pos underspecification
     6000
The relevant number of smesmn entries for the Oulu conference is then 6000!

