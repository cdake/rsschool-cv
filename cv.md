# Daniyar Boranbayev

*************

### Contact information

** Email: ** daniyarboran@yandex.ru
** Telegram: ** PROProcrastinator
** Discord: ** Daniyar#9698(@cdake)

*************

### About Me

This is my another one attempt to jump in to IT industry. Currently I work in construction inudstry as planning engineer.
In my work I often use Excel and few times I have used VBA language for my work. Let's admit it is kind of programming.
Create for fun Web application using python programming language, Flask framework, CSS and HTML, and Telegram-bot as well. 
Now I want to change my career path and decide to work in web-development. 
Will see...

*************
### Skills
* MS Excel
* Primavera
* Python
* HTML5, CSS

*************
### Code example

** All Star Code Challenge #20 from CODEWARS **

Create a function called addArrays() that combines two arrays of equal length, summing each element of the first with the corresponding element in the second, returning the "combined" summed array.
Raise an error if input arguments are not of equal length.

```
addArrays([1,2],[4,5]); // => [5,7]
addArrays([1,2,3],[4,5]); // => Error
```

** Note: **
Expect array input to either contain numbers or strings only
The function should also allow for concatenating string

```addArrays(["a"],["b"]) // => ["ab"]
```

* Solution *
```
def add_arrays(array1, array2): 
    
    lenarr1 = len(array1)
    lenarr2 = len(array2)
    if lenarr1 == lenarr2:
        result = []
        for i in range(lenarr1) and range(lenarr2):
            if type(array1[i]) == type(array2[i]):
                result.append(array1[i]+array2[i])
            else:
                result = ''
                result = 'Error'
    return result
```

### Courses
* HTML, CSS on https://freecodecamp.org
* RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)


### Languages
* Kazakh - native
* Russian - fluent
* English - can speak, read, write