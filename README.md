# project-new
This is repository
import java.io.*;
import java.util.*;


public class hashMapFunctions {
    public static void main(String[] args) {
        HashMap<Integer,String> hashMap = new HashMap<>();
        //functionality of put() fun
        hashMap.put(1,"Rahul");
        hashMap.put(2,"Arvind");
        hashMap.put(3,"Riddhi");
        hashMap.put(4,"Happy");

        System.out.println("HashMap of the given data is : " + hashMap);
        //functionality of get() fun
        String result=hashMap.get(2);
        System.out.println("Value for the given key is : " + result);

        //functionality of the containKey()
        System.out.println(hashMap.containsKey(2));

        //funationality of the remove()
        hashMap.remove(1);
        System.out.println("Updated hashmap : " + hashMap);
        
        //iterating using the for loop
        for(Map.Entry<Integer,String> e:hashMap.entrySet()){
            System.out.println("Hashmap is : ");
            System.out.println(e.getKey()+ " : " + e.getValue());
        }




    }
    
}
