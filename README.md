# Makefile
<h3> To use Makefile: </h3>

type “make” <br/>
– It will figure out which .c files need to be
recompiled and turned into .o files <br/>
• If the .c file is newer than the .o file or
• the .o file does not exist <br/>
– Figures out if the program needs to be relinked <br/>
• If any of the .o files changed or
• If the program does not exist
<br/>
Or type “make clean” <br/>
– Deletes: <br/>
• all the .o files <br/>
• all the ~ files (from emacs) <br/>
• the program itself <br/>
– Leaves:<br/>
• .c files<br/>
• .h files<br/>
• Makefile<br/>

# Libft
First project - library of C functions
Name  | Status
------------- | -------------
isalpha     |  ✅ 
isdigit   |  ✅ 
isalnum|✅ 
isascii|✅ 
isprint| ✅ 
strlen|✅ 
memset|✅ 
bzero|✅ 
memcpy|✅ 
memmove|✅ 
strlcpy|✅ 
strlcat|✅ 
toupper|✅ 
tolower| ✅ 
strchr|✅ 
strrchr|✅ 
strncmp|✅ 
memchr|✅ 
memcmp|✅ 
strnstr|✅ 
atoi|✅ 

**Using malloc()**

Name  | Status
------------- | -------------
calloc    |  ✅ 
strdup   | ✅ 

**Part 2**

Name  | Status
------------- | -------------
ft_substr    |  ✅ 
ft_strjoin   | ✅ 
ft_strtrim  | ✅ 
ft_split  | ✅ 
ft_itoa  | ✅ 
ft_strmapi   |✅  
ft_striteri  | ✅ 
ft_putchar_fd  | ✅ 
ft_putstr_fd  | ✅ 
ft_putendl_fd| ✅ 
ft_putnbr_fd| ✅ 


**Bonus**
Name  | Status
------------- | -------------
ft_lstnew   |  ✅ 
ft_lstadd_front   | ✅ 
ft_lstsize | ✅ 
ft_lstlast | ✅ 
ft_lstadd_back  | ✅ 
ft_lstdelone | ✅ 
ft_lstclear| ✅ 
ft_lstiter| ✅ 
ft_lstmap| ✅ 
