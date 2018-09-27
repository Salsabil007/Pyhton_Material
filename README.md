# PY COMMANDS
## 1. Taking User Input 
```
name = raw_input("What is your name? ")

print(name)

a=input("enter number one: ")
print(type(a))
b=input("enter number two: ")
print(a+b)

print('his name\'s arabi')
```
## 2. If Else 
```
a=input("enter number one: ")
b=input("enter number two: ")
if a%2 == 0:
    
        print("yes")
        a=a+2
        print(a)

elif b%2 == 1:
    print("no")
else:
    print("shit")
```
## 3. For Loop 
```
a=input("enter number one: ")
b=input("enter number two: ")
if a%2 == 0:
    
        print("yes")
        a=a+2
        print(a)

elif b%2 == 1:
    print("no")
else:
    print("shit")

```
## 4. While Loop 
```
a=int(input("enter number one: "))
b=int (input("enter number two: "))
count=0
while (count<=a):
    print(count)
    count=count+1
```
## 5. Function
```
def function1(a,b):
    count = 0
    while (count <= a):
        print(count)
        count = count + 1
    return count

x=function1(3,4)
print(x)
```
## 6. List 
```
c=["mom","dad","vaiya","apu","tasu habu","asu habu","ifu gabu"]
for i in range(0,len(c)):
    print(c[i])
print(len(c))
print(c[-7])
print c   //prints: ["mom","dad","vaiya","apu","tasu habu","asu habu","ifu gabu"]
```
### 6.1. list another way
```
c={}
c[0]=1
c[1]=2
c[2]=3
c[3]=4
c[4]=5
for i in c:
    print(c[i])

```

### 6.2. list functions :
```
list = ['larry', 'curly', 'moe']
  list.append('shemp')         ## append elem at end
  list.insert(0, 'xxx')        ## insert elem at index 0
  list.extend(['yyy', 'zzz'])  ## add list of elems at end
  print list  ## ['xxx', 'larry', 'curly', 'moe', 'shemp', 'yyy', 'zzz']
  print list.index('curly')    ## 2

  list.remove('curly')         ## search and remove that element
  list.pop(1)                  ## removes and returns 'larry'
  print list  ## ['xxx', 'moe', 'shemp', 'yyy', 'zzz']
```
### 6.3. list build up :
```
  list = []          ## Start as the empty list 
  list.append('a')   ## Use append() to add elements
  list.append('b')
```

## 7. String 
```
raw = r'this\t\n and that'
  print raw     ## this\t\n and that
    
  multi = """It was the best of times.
  It was the worst of times."""
```

### 7.1. String Methods :
```
    s.lower(), s.upper() -- returns the lowercase or uppercase version of the string
    s.strip() -- returns a string with whitespace removed from the start and end
    s.isalpha()/s.isdigit()/s.isspace()... -- tests if all the string chars are in the various character classes
    s.startswith('other'), s.endswith('other') -- tests if the string starts or ends with the given other string
    s.find('other') -- searches for the given other string (not a regular expression) within s, and returns the first index where it begins or -1 if not found
    s.replace('old', 'new') -- returns a string where all occurrences of 'old' have been replaced by 'new'
    s.split('delim') -- returns a list of substrings separated by the given delimiter. The delimiter is not a regular expression, it's just text. 'aaa,bbb,ccc'.split(',') -> ['aaa', 'bbb', 'ccc']. As a convenient special case s.split() (with no arguments) splits on all whitespace chars.
    s.join(list) -- opposite of split(), joins the elements in the given list together using the string as the delimiter. e.g. '---'.join(['aaa', 'bbb', 'ccc']) -> aaa---bbb---ccc
```

## 8. Tuple 
```
tuple=(1,2,3,2,5,6,"dhoni","shus")
tuple1=("pong",9)
print tuple[:8]
tuple2=tuple+tuple1
print tuple2
```


## 9. Files

```
f = open('file.txt', 'rU')
for line in f:
    print line,

f.close()

```


# REFERENCES
## necessary links
1. https://developers.google.com/edu/python/dict-files
2. https://www.tutorialspoint.com/python/python_tuples.htm
















































