# libft42
YOUR VERY FIRST OWN LIBRARY ---- >> This project is your first project as a student at 42. You will need to recode a few functions of the C standard library as well as some other utility functions that you will use during your whole cursus.
# ABOUT LIBFT-PROJECT :
Programming in C can be very tedious when you don't have access to the very useful standard functions.
This project gives you the opportunity to rewrite those functions to understand them and learn to use them.
The library will help you for your future projects in C. Through this project, you have the opportunity
to extend your list of functions in your own way! For more detailed information, look at the subject of this project.

**WHAT IS MAKEFILE ?** :  Makefiles are files, usually called makefile or Makefile, used by the make program to perform a set of actions, such as compiling a project, checking in a document, updating a site, etc. This article will show how makefile works by compiling a small C project.So Make is a very general tool allowing to automate the compilation of a project. Suppose that the project consists of the following C sources: main.c, structure.c, and operation.c . It is possible to compile this project in three different ways, the following parts specify these different steps.

тЪая╕П NOTE тЪая╕П : To be successful with moulinette on this project I had to put all the files in the same directory. I have just put them in folders and modified the Makefile to have a better organized repository.
# LIST OF FUNCTIONS :

---> Functions from <ctype.h> library

рнб [ft_isascii](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_isascii.c) - test for ASCII character.                                         
рнб [ft_isalnum](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_isalnum.c) - alphanumeric character test.                                    
рнб [ft_isalpha](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_isalpha.c) - alphabetic character test.                                      
рнб [ft_isdigit](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_isdigit.c) - decimal-digit character test.                                    
рнб [ft_isprint](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_isprint.c) - printing character test (space character inclusive).            
рнб [ft_tolower](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_tolower.c) - upper case to lower case letter conversion.                      
рнб [ft_toupper](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_toupper.c) - lower case to upper case letter conversion.                      

---> Functions from <stdlib.h> library

рнб [ft_atoi](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_atoi.c) - convert ASCII string to integer.                                    
рнб [ft_calloc](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_calloc.c) - memory allocation.

---> Functions from <strings.h> library

рнб [ft_bzero](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_bzero.c) - write zeroes to a byte string.                                      
рнб [ft_memset](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_memset.c) - write a byte to a byte string.                                    
рнб [ft_memchr](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_memchr.c) - locate byte in byte string.                                        
рнб [ft_memcmp](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_memcmp.c)- compare byte string.                                                
рнб [ft_memove](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_memove.c) - copy byte string.                                                  
рнб [ft_memcpy](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_memcpy.c) - copy memory area.                                                  

---> Functions from <string.h> library

рнб [ft_strlen](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_strlen.c)- find length of string.                                              
рнб [ft_strchr](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_strchr.c) - locate character in string (first occurrence).                    
рнб [ft_strrchr](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_strrchr.c) - locate character in string (last occurence).                    
рнб [ft_strntr](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_strnstr.c) - locate a substring in a string (size-bounded).                    
рнб [ft_strncmp](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_strncmp.c)- compare strings (size-bounded).                                  
рнб [ft_strdup](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_strdup.c) - save a copy of a string (with malloc).                            
рнб [ft_strlcpy](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_strlcpy.c) - size-bounded string copying.                                    
рнб [ft_strlcat](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_strlcat.c) - size-bounded string concatenation.                              

---> Non-standard functions

рнб [ft_itoa](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_itoa.c) - convert integer to ASCII string.                                      
рнб [ft_substr](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_substr.c) - extract substring from string.                                    
рнб [ft_strtrim](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_strtrim.c) - trim beginning and end of string with the specified characters.  
рнб [strjoin](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_strjoin.c) - concatenate two strings into a new string (with malloc).            
рнб [ft_split](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_split.c) - split string, with specified character as delimiter, into an array of strings.                                                                                                                                              
рнб [ft_strmapi](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_strmapi.c) - create new string from modifying string with specified function.                                                                                                                                                
рнб [ft_striteri](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_striteri.c) -applies the fonction f to each character of the string passed as argument , and passing it's index as firt argument                                                                                                    
рнб [ft_putchar_fd](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_putchar_fd.c) - output a character to given file.                          
рнб [ft_putstr_fd](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_putstr_fd.c) - output string to given file.                                
рнб [ft_putendl_fd](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_putendl_fd.c) - output string to given file with newline.                  
рнб [ft_putnbr_fd](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_putnbr.c) - output integer to given file.                                  

---> Linked list functions ( BONUS PART)

рнб [ft_lstnew](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_lstnew.c) - create new list.                                                  
рнб [ft_lstsize](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_lstsize.c) - count elements of a list.                                        
рнб [ft_lstlast](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_lstlast.c) - find last element of list.                                      
рнб [ft_lstadd_back](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_lstadd_back.c) - add new element at end of list.                          
рнб [ft_lstadd_front](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_lstadd_front.c) - add new element at beginning of list.                  
рнб [ft_lstdelone](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_lstdelone.c) - delete element from list.                                    
рнб [ft_lstclear](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_lstclear.c) - delete sequence of elements of list from a starting point.    
рнб [ft_lstiter](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_lstiter.c) - apply function to content of all list's elements.                
рнб [ft_lstmap](https://github.com/SWEETBEAVER/LIBFT-PROJECT/blob/main/libft/ft_lstmap.c) - apply function to content of all list's elements into new list.    
