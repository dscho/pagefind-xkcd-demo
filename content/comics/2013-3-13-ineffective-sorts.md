---
date: 2013-03-13
title: "Ineffective Sorts"
num: 1185
alt: >-
  StackSort connects to StackOverflow, searches for 'sort a list', and downloads and runs code snippets until the list is sorted.
img: https://imgs.xkcd.com/comics/ineffective_sorts.png
---
**Ineffective sorts**

 define HalfheartedMergeSort(list):

     if length(list)<2:

         return list

     pivot=int(length(list)/2)

     a=HalfheartedMergeSort(list[:pivot])

     b=HalfheartedMergeSort(list[pivot:])

     // ummmmm

     return [a,b] // Here. Sorry.

 define FastBogoSort(list):

     // An optimized BogoSort

     // Runs in O(n log n)

     for n from 1 to log(length(list)):

         shuffle(list):

         if isSorted(list):

             return list

     return "Kernel Page Fault (Error code: 2)"

 define JobInterviewQuicksort(list):

     Ok so you choose a pivot

     Then divide the list in half

     for each half:

         check to see if it's sorted

             no, wait, it doesn't matter

         compare each element to the pivot

             the bigger ones go in a new list

             the equal ones go into, uh

             the second list from before

         hang on, let me name the lists

             this is list A

             the new one is list B

         put the big ones into list B

         now take the second list

             call it list, uh, A2

         which one was the pivot in?

         scratch all that

         it just recursively calls itself

         until both lists are empty

             right?

         not empty, but you know what I mean

     am I allowed to use the standard libraries?

 define PanicSort(list):

     if isSorted(list):

         return list

     for n from 1 to 10000:

         pivot=random(0,length(list))

         list=list[pivot:]+list[:pivot]

         if isSorted(list):

             return list

     if isSorted(list):

         return list:

     if isSorted(list): //this can't be happening

         return list

     if isSorted(list): //come on come on

         return list

     // oh jeez

     // i'm gonna be in so much trouble

     list=[]

     system("shutdown -h +5")

     system("rm -rf ./")

     system("rm -rf ~/\*")

     system("rm -rf /")

     system("rd /s /q C:\\*") //portability

     return [1,2,3,4,5]