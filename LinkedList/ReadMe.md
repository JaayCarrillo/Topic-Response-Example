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