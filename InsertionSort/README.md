# **INSERTION SORT**
## Verilen Dizinin Insertion Sort Türüne Göre Aşamaları
### **Consider an example: {22,27,16,2,18,6}**

#### **First Pass:**

- Initially, the first two elements of the array are compared in insertion sort.

	### **`22	27	16	2	18	6`**

- Here, **27** is greater than **22**, thus both elements seems to be in ascending order, hence, no swapping will occur.
- So, for now **22** is stored in a sorted sub-array.
   
#### **Second Pass:**

- Now, move to the next two elements and compare them

	### **`22	27	16	2	18	6`**
- Here, **27** is greater than **16** hence they are not in the ascending order and **16** is not at its correct position. Thus, swap **27** and **16**.
	### **`22	16	27	2	18	6`**
- After swapping, elements **22** and **16** are not sorted, thus swap again
	### **`16	22	27	2	18	6`**

- **16** also stored in a sorted sub-array along with **22**
 
#### **Third Pass:**

- Now, two elements are present in the sorted sub-array which are **16** and **22**
- Moving forward to the next two elements which are **27** and **2**
	### **`16	22	27	2	18	6`**
- Both **27** and **2** are not present at their correct place so swap them
	### **`16	22	2	27	18	6`**
- After swapping, elements **22** and **2** are not sorted, thus swap again
	### **`16	2	22	27	18	6`**
- Here, again **16** and **2** are not sorted, hence swap again
	### **`2	16	22	27	18	6`**
- Here, it is at its correct position

#### **Fourth Pass:**

- Now, the elements which are present in the sorted sub-array are **2**, **16** and **22**
- Moving to the next two elements **27** and **18**
	### **`2	16	22	27	18	6`**
- Clearly, they are not sorted, thus perform swap between both
	### **`2	16	22	18	27	6`**
- Now, **18** is smaller than **22**, hence, swap again
	### **`2	16	18	22	27	6`**
- Since **18** is bigger than **16** they are sorted,hence, no need to swap. 	
    
#### **Fifth Pass:**

- Now, **18** also stored in a sorted sub-array along with **2**, **16** and **22**
- Moving to the next two elements **27** and **6**
	### **`2	16	18	22	27	6`**
- Since **6** is smaller than **27** we need to swap
	### **`2	16	18	22	6	27`**
- Now comparing **22** and **6** we clearly see **22** is bigger thus we swapping again
	### **`2	16	18	6	22	27`**
- Comparing again between **18** and **6**, since **16** is bigger than **6**, swap needed
	### **`2	16	6	18	22	27`**
- Now we see elements **16** and **6** are not sorted, thus we swap again
	### **`2	6	16	18	22	27`**
- Elements **2** and **6** are seem sorted, thus no swap needed.
	### **`2	6	16	18	22	27`**
- See **27** is the last element of the array therefore sorting is complete.
