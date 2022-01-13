* # **Proje 2**

[16,21,11,8,12,22]

### **a.** 

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

### **b.** 

Big-O gösterimini yazınız.
***

* # **Çözümler**

### **a.** 

[16,21,11,8,12,22]

[16]--[21,11]-----[8,12]--[22]

[16]--[21]--[11]-----[8]--[12]--[22]

[16]--[11,21]-----[8,12]--[22]

[11,16,21]-----[8,12,22]

[8,11,12,16,21,22]

### **b.** 

Big-O gösterimi:

"n" sürede bittiği varsayarsak

O(nlogn)