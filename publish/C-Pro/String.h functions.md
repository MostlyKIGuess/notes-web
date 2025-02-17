

- Functions that I find useful in cp:
- s.substr(int index1,int index2) - gives the sub string from index1 to index2.



|Sr.No.|Function & Description|
|---|---|
|1|[void *memchr(const void *str, int c, size_t n)](https://www.tutorialspoint.com/c_standard_library/c_function_memchr.htm)<br><br>Searches for the first occurrence of the character c (an unsigned char) in the first n bytes of the string pointed to, by the argument _str_.|
|2|[int memcmp(const void *str1, const void *str2, size_t n)](https://www.tutorialspoint.com/c_standard_library/c_function_memcmp.htm)<br><br>Compares the first n bytes of _str1_ and _str2_.|
|3|[void *memcpy(void *dest, const void *src, size_t n)](https://www.tutorialspoint.com/c_standard_library/c_function_memcpy.htm)<br><br>Copies n characters from src to _dest_.|
|4|[void *memmove(void *dest, const void *src, size_t n)](https://www.tutorialspoint.com/c_standard_library/c_function_memmove.htm)<br><br>Another function to copy n characters from _str2_ to _str1_.|
|5|[void *memset(void *str, int c, size_t n)](https://www.tutorialspoint.com/c_standard_library/c_function_memset.htm)<br><br>Copies the character c (an unsigned char) to the first n characters of the string pointed to, by the argument _str_.|
|6|[char *strcat(char *dest, const char *src)](https://www.tutorialspoint.com/c_standard_library/c_function_strcat.htm)<br><br>Appends the string pointed to, by _src_ to the end of the string pointed to by _dest_.|
|7|[char *strncat(char *dest, const char *src, size_t n)](https://www.tutorialspoint.com/c_standard_library/c_function_strncat.htm)<br><br>Appends the string pointed to, by _src_ to the end of the string pointed to, by _dest_ up to n characters long.|
|8|[char *strchr(const char *str, int c)](https://www.tutorialspoint.com/c_standard_library/c_function_strchr.htm)<br><br>Searches for the first occurrence of the character c (an unsigned char) in the string pointed to, by the argument _str_.|
|9|[int strcmp(const char *str1, const char *str2)](https://www.tutorialspoint.com/c_standard_library/c_function_strcmp.htm)<br><br>Compares the string pointed to, by _str1_ to the string pointed to by _str2_.|
|10|[int strncmp(const char *str1, const char *str2, size_t n)](https://www.tutorialspoint.com/c_standard_library/c_function_strncmp.htm)<br><br>Compares at most the first n bytes of _str1_ and _str2_.|
|11|[int strcoll(const char *str1, const char *str2)](https://www.tutorialspoint.com/c_standard_library/c_function_strcoll.htm)<br><br>Compares string _str1_ to _str2_. The result is dependent on the LC_COLLATE setting of the location.|
|12|[char *strcpy(char *dest, const char *src)](https://www.tutorialspoint.com/c_standard_library/c_function_strcpy.htm)<br><br>Copies the string pointed to, by _src_ to _dest_.|
|13|[char *strncpy(char *dest, const char *src, size_t n)](https://www.tutorialspoint.com/c_standard_library/c_function_strncpy.htm)<br><br>Copies up to n characters from the string pointed to, by _src_ to _dest_.|
|14|[size_t strcspn(const char *str1, const char *str2)](https://www.tutorialspoint.com/c_standard_library/c_function_strcspn.htm)<br><br>Calculates the length of the initial segment of str1 which consists entirely of characters not in str2.|
|15|[char *strerror(int errnum)](https://www.tutorialspoint.com/c_standard_library/c_function_strerror.htm)<br><br>Searches an internal array for the error number errnum and returns a pointer to an error message string.|
|16|[size_t strlen(const char *str)](https://www.tutorialspoint.com/c_standard_library/c_function_strlen.htm)<br><br>Computes the length of the string str up to but not including the terminating null character.|
|17|[char *strpbrk(const char *str1, const char *str2)](https://www.tutorialspoint.com/c_standard_library/c_function_strpbrk.htm)<br><br>Finds the first character in the string _str1_ that matches any character specified in _str2_.|
|18|[char *strrchr(const char *str, int c)](https://www.tutorialspoint.com/c_standard_library/c_function_strrchr.htm)<br><br>Searches for the last occurrence of the character c (an unsigned char) in the string pointed to by the argument _str_.|
|19|[size_t strspn(const char *str1, const char *str2)](https://www.tutorialspoint.com/c_standard_library/c_function_strspn.htm)<br><br>Calculates the length of the initial segment of _str1_ which consists entirely of characters in _str2_.|
|20|[char *strstr(const char *haystack, const char *needle)](https://www.tutorialspoint.com/c_standard_library/c_function_strstr.htm)<br><br>Finds the first occurrence of the entire string _needle_ (not including the terminating null character) which appears in the string _haystack_.|
|21|[char *strtok(char *str, const char *delim)](https://www.tutorialspoint.com/c_standard_library/c_function_strtok.htm)<br><br>Breaks string _str_ into a series of tokens separated by _delim_.|
|22|[size_t strxfrm(char *dest, const char *src, size_t n)](https://www.tutorialspoint.com/c_standard_library/c_function_strxfrm.htm)<br><br>Transforms the first **n** characters of the string **src** into current locale and places them in the string **dest**.|