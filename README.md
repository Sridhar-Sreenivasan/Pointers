# Pointers-in-cpp 

---

## Aim  
To understand and implement the concept of **pointers in C++** using:  
1. Value pointed to by a pointer (integer).  
2. Changing the value pointed to by a pointer in an array.  
3. Incrementing the pointer and accessing values.  

---

## Theory  

- **Pointer:** A variable that stores the memory address of another variable.  
- **Dereferencing:** Accessing the value stored at the memory address using `*` operator.  
- **Pointer Arithmetic:** Incrementing/decrementing a pointer moves it to the next/previous memory location depending on the datatype.  

### Key Notes  
- `int *p` → declares a pointer to an integer.  
- `p = &x` → assigns the address of variable `x` to pointer `p`.  
- `*p` → retrieves (dereferences) the value stored at the address.  
- Incrementing a pointer (`p++`) moves it to the next element in memory (for arrays).  

---

## Algorithm  

### Experiment 9A – Value pointed to by a pointer  
1. Start the program.  
2. Declare an integer variable `x`.  
3. Assign its address to a pointer `p`.  
4. Display the address of `x`.  
5. Display the value of `x` using pointer `*p`.  
6. End.  

---

### Experiment 9B – Changing value pointed to by a pointer in array  
1. Start the program.  
2. Declare an array of integers.  
3. Assign the base address of array to a pointer.  
4. Display the first element before change.  
5. Modify the first element using pointer dereferencing.  
6. Display the first element after change.  
7. End.  

---

### Experiment 9C – Incrementing the pointer  
1. Start the program.  
2. Declare an array of integers.  
3. Assign the base address to a pointer `p`.  
4. Display the value pointed by `p`.  
5. Increment the pointer (`p++`).  
6. Display the new value pointed by `p`.  
7. End.  

---

# Conclusion 

- Understood how **pointers** can be used to access the value and address of variables.  
- Verified that using a pointer, we can **directly modify array elements** without accessing them by index.  
- Learned how **incrementing a pointer** moves it to the next memory location (next element in an array).  
- Experiment successfully demonstrated the **power and flexibility of pointers** in C++.  
