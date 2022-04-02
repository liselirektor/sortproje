# Insetion Sort



``` [22,27,16,2,18,6] ``` -> Insertion Sort
 
- Aşama 0 ` [22,27,16,2,18,6] ` = n
- Aşama 1 ` [2,27,16,22,18,6] ` = (n-1)
- Aşama 2 ` [2,6,16,22,18,27] ` = (n-2)
- Aşama 3 ` [2,6,16,18,22,27] ` = (n-3) 
***(complate)***
---
## Big O Notation
```
n.(n-1)+(n-2)+ ... +(1) =n^2+n/2 = O(n^2)
```
---

## Time Complexity

- Worst Case Durumu  
    - O(n^2) olur <br>
- Average Case Durumu  
    - O(n^2) olur. <br>
- Best Case Durumu  
    - O(n^2) olur.
---
## Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? 

<p>Average case durumudur. Çünkü istenilen durumu gösterir</p>

---
## `[7,3,5,8,2,9,4,15,6]`
- Aşama 1 ``[2,3,5,8,7,9,4,15,6]``-> 2-7
- Aşama 2 ``[2,3,4,8,7,9,5,15,6]``-> 4-5
- Aşama 3 ``[2,3,4,5,7,9,8,15,6]``-> 5-8
- Aşama 4 ``[2,3,4,5,6,9,8,15,7]``-> 6-7
- Aşama 5 ``[2,3,4,5,6,7,8,15,9]``-> 9-7
- Aşama 6 ``[2,3,4,5,6,7,8,9,15]``-> 15-9 <br>
>``[2,3,4,5,6,7,8,15,9]``-> ***Complate***
