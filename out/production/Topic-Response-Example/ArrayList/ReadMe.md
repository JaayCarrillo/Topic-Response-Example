# ArrayList Example
 ```
 package ArrayList;

import java.util.ArrayList;

public class arrayListExample {
// ArrayList - passing a ' String ' as a reference type //
// reference type named ' appleProducts '
static ArrayList<String> appleProducts = new ArrayList<String>();
 ```

    public static void main(String[] args) {
        // array of [4] apple products //
    appleProducts.add("Apple iPhone" + " "+ "[0]"); // [0] //
    appleProducts.add("Apple MacBook" + " "+"[1]"); // [1] //
    appleProducts.add("Apple iMac" + " "+"[2]"); // [2] //
    appleProducts.add("Apple Watch" + " "+"[3]"); // [3] //
    appleProducts.add("Apple airPods" + " "+"[4]"); // [4] //
    // for loop to loop through the string of products //
        // .size()// is used && returns the number of elements in the array.
        // instead of using .length() which you would use in a 'linkedList'
        // we use the .size() function
```
 for(int i = 0; i < appleProducts.size(); i++){
        System.out.println(appleProducts.get(i)); // print to console
    }
    }

}
```
## Console Output : Array of Products
# -----------------------------------
`Apple iPhone [0]
Apple MacBook [1]
Apple iMac [2]
Apple Watch [3]
Apple airPods [4]`
