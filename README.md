﻿# **Merge-Sort**

### Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

# **Çözüm**
 ikiye bölüp kendi aralarında sıralayıp tek hücre olana kadar devam edip  
 sonra birleştirip  sıralama metodu  

 16,21,11 ----- 8,12,22

 16 ---- 21,11 ---- 8,12 ---- 18  
 16 -- 21 -- 11 -- 8 -- 12 -- 18  
 16 -- 11,21 -- 8,12 -- 18  
 11,16,21 -- 8,12,18  
 8,11,12,16,18,21  
 
 # **Big-O = O(nlogn)**



#www.patika.dev
