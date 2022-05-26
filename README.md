# Insertion-Sort
Patika.dev
#Proje 1

[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

|22|**16**|27|2|18|6|
|16|22|27|**2**|18|6|
|2|16|22|27|**18**|6|
|2|16|18|22|27|18|**6**|
|2|6|16|18|22|27|


Big-O gösterimini yazınız.

  - `O(n^2)`
Time Complexity
  - worst case: `O(n^2)` - aranan sayının en sonda olması veya dizinin içinde hiç olmaması
  - best case: `O(n)` - aranan sayının en başta olması
  - avarage case: `O(n^2)` - aranan sayının baş ve son hariç, herhangi bir indekste olması

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
  - Sayı başta veya sonda olmadığı için worst case ile aynıdır: `O(n^2)`

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1- |3|7|5|8|2|9|4|15|6|
2- |3|5|7|8|2|9|4|15|6|
3- |3|5|7|2|8|9|4|15|6|
4- |3|5|2|7|8|9|4|15|6|
