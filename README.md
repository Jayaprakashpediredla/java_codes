Let's Discuss Concepts here....

Why main() is static method?
-> Because main() is called using class name by JVM.
Java Hello

-> It will be converted to a call to main as follows,
HEllo.main(parameter)


@Override Annotation
-> Indicates that a method declaration in subclass is intended to override a method declaration in a superclass
-> If a method annotated does not override super class method, compiler generates error message.



**Collections Framework**

Interface           Implementing classes
*************************************************
Collection          
Set                 HashSet
SortedSet           TreeSet
List                ArrayList / Vector / LinkedList
Maps                HashMap / HashTable
SortedMap           TreeMap
Queue               LinkedList / PriorityQueue


Methods in Collection Interface 
add()
addAll()
clear()
contains()
containsAll()
isEmpty()
iterator()
remove()
removeAll()
retainAll()
size()
toArray()
removeIf()
stream()
paralleStream()