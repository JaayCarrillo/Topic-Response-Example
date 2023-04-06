# LinkedList Example
```
import java.util.LinkedList;

public class LinkedListExample {
    // Double Linked List
    /**
     * Operations that index into the list will traverse
     * the list from the beginning or the end, whichever is closer to the specified index.
     */
    static LinkedList<String> listExample = new LinkedList<String>();

    public static void main(String[] args) {
        //.push() Pushes an element onto the stack represented by this list //
        listExample.push("Spiderman");
        listExample.push("Thor");
        listExample.push("Iron-Man");
        listExample.push("Hulk");
    // prints our list
        System.out.println(listExample);
    }
}
```
## Console Output: 
```
[Hulk, Iron-Man, Thor, Spiderman]
```

# LinkedList in Queue example 
```
public static void main(String[] args) {
        //.push() Pushes an element onto the stack represented by this list //
        //listExample.push("Spiderman");
        //listExample.push("Thor");
        //listExample.push("Iron-Man");
        //listExample.push("Hulk");

        // Set our LinkedList as a queue using the .offer() && .pull() methods
        listExample.offer("Spiderman");
        listExample.offer("Thor");
        listExample.offer("Iron-Man");
        listExample.offer("Hulk");
        // Output will print our list in a queue
    // prints our list
        System.out.println(listExample);
    }

```
## Console Output: 
```
[Spiderman, Thor, Iron-Man, Hulk]
```
# Using .poll() method 
```
// Set our LinkedList as a queue using the .offer() && .pull() methods
        listExample.offer("Spiderman");
        listExample.offer("Thor");
        listExample.offer("Iron-Man");
        listExample.offer("Hulk");
        // Retrieves and removes the head (first element) of this list. 
        listExample.poll();
        // Output will print our list in a queue
    // prints our list
        System.out.println(listExample);
    }
```
## Console Output: 
```
[Thor, Iron-Man, Hulk]
```
# Removing and Adding Elements 
```
// Set our LinkedList as a queue using the .offer() && .pull() methods
        listExample.offer("Spiderman"); // [0]
        listExample.offer("Thor"); // [1]
        listExample.offer("Iron-Man"); // [2]
        listExample.offer("Hulk"); // [3]
        // Retrieves and removes the head (first element) of this list.
        //listExample.poll();
        listExample.add(0,"Black-Hawk"); // add element at [0] 
        listExample.add(3,"Ant-Man"); // adds element at index[3] 

        listExample.remove("Thor"); // removes index[1] completely
        // Output will print our list in a queue
    // prints our list
        System.out.println(listExample);
    }
```
## Console Output: 
```
[Black-Hawk, Spiderman, Ant-Man, Iron-Man, Hulk]
```