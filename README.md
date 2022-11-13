# DynamicArray

Реализация динамического массива.  

Реализованы следующие методы:
 
- Array() 
- Array(int capacity)  
- Array(const Array &array)  
- ~Array()  
- Array(Array &&array)  
- Array &operator=(Array &array)  
- Array &operator=(Array &&array)  
- int insert(const T &value)  
- int insert(int index, const T &value)  
- void remove(int index)  
- const T &operator[](int index) const  
- T &operator[](int index)  
- int size() const  
- int capacity() const  
- class Iterator  
- Iterator iterator()  
- Iterator reverseIterator()  
