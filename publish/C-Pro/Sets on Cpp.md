Sets are containers that store unique elements following a specific order. Here are some of the frequently used member functions of sets:


```cpp
    set<int>s; //Creates a set of integers.
    int length=s.size(); //Gives the size of the set.
    
    s.insert(x); //Inserts an integer x into the set s
    
	 s.erase(val); //Erases an integer val from the set s.
	 
	set<int>::iterator itr=s.find(val); //Gives the iterator to the element val if it is found otherwise returns s.end().
	
 Ex: set<int>::iterator itr=s.find(100); //If 100 is not present then it==s.end().

    ```

