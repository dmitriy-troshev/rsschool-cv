# Dmitriy Troshev
---
![It's me](IMG_20210627_210742.jpg)

## Contacts

**Phone:** +375 29 197 98 91

**E-mail:** dmitriy_troshev@mail.ru

**VK:** [https://vk.com/dmitriy_troshev](https://vk.com/dmitriy_troshev)

**Instagram:** [https://www.instagram.com/dimax3452/?hl=ru](https://www.instagram.com/dimax3452/?hl=ru)

**Adress:** Belarus, Gomel

## ABOUT MYSELF

Hi, my name is Dmitriy. I gradueted Gomel State Technical university in 2009. My specialization is Power Engineering. In 2012 I graduated from magistracy, and in 2016 graduated postgraduate studies, and have master's and researcher degree in technical sciences. From 2009 to 2017 I was working in the university as a teacher and  as a researcher in energy efficiency. In 2017 I changed my work and started carrier at the power station as a engineer. In 2020 I started my own buissnes in energy efficiency. One year ago I started learnig coding because programming is the most usefull skill in our life.

## Languages:
**Russian:** *native*
**English:** *pre-intermediate*
**Ukrainian:** *intermediate*

## Code Example
Example of my code from **coursera.org** (course *Основы программирования на Python*). **Task:** count average grade by classes. Grades is saved in input.txt, answers have to output in output.txt.
```
n_9 = 0
n_10 = 0
n_11 = 0
g_9 = 0
g_10 = 0
g_11 = 0

inFile = open('input.txt', 'r', encoding='utf8')
outFile = open('output.txt', 'w', encoding='utf8')

while True:
    l1 = inFile.readline()
    st_list = l1.split()
    if not l1:
        break
    n = st_list[2]
    g = st_list[3]
    n_cl = int(n)
    grade = int(g)
    if n_cl == 9:
        n_9 += 1
        g_9 += grade
    elif n_cl == 10:
        n_10 += 1
        g_10 += grade
    elif n_cl == 11:
        n_11 += 1
        g_11 += grade

print(g_9/n_9, g_10/n_10, g_11/n_11, sep=' ')
```


 
 