# Patika.dev Merge Sort

* Patika Profil Linki:  https://app.patika.dev/sakas

## Ödev 


* [16,21,11,8,12,22]

 1. Yukarıda verilen dizinin merge sort türüne göre aşamalarını yazınız.
 
    *  Sorting Öncesi - [16,21,11,8,12,22]
 
        * Step 1
        
          ֎ Dizi recursive olarak ikiye bölünür 
          
                      >        [16, 21, 11, 8, 12, 22]
                      >       [16, 21, 11]  [8, 12, 22] 
                      >     [16, 21]  [11]  [8, 12]  [22] 
                      >   [16]  [21]  [11]  [8]  [12]  [22]
         
        * Step 2 
          
          ֎ Dizi elemanları recursive olarak sıralarak birleştirilir
          
                      >   [16]  [21]  [11]  [8]  [12]  [22]
                      >     [16, 21]  [11]  [8, 12]  [22]
                      >       [11, 16, 21]  [8, 12, 22]
                      >        [8, 11, 12, 16, 21, 22]  
          
     * Sorting Sonrası - [8, 11, 12, 16, 21, 22]   
 
 2. Big-O gösterimini yazınız.
 
    * O(nlogn)
    
