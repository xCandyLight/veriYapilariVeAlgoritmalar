## 1. Soru : [22,27,16,2,18,6] -> Insertion Sort // Verilen dizinin sort türüne göre aşamalarını yazınız.

Cevap;

1. Adım : [16,22,27*,2,18,6]
2. Adım : [2,16,22,27*,18,6]
3. Adım : [2,16,18,22,27*,6]
4. Adım : [2,6,16,18,22,27*]

## 2. Soru : Big-O gösterimini yazınız.

Cevap;

n+(n-1)+(n-2)+(n-3)+(n-4)+1= (n(n+1))/2= n^2
Big-O = n^2 

## 3. Soru : Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer yazınız.

Cevap;

Average Case : Aradığımız sayının ortada olması.

## 4. Soru : [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Cevap;

[7,3,5,8,2,9,4,15,6] -> [2*,3,5,8,7*,9,4,15,6] -> [2,3,5,8,7,9,4,15,6] -> [2,3,4*,8,7,9,5*,15,6] -> [2,3,4,5*,7,9,8*,15,6]