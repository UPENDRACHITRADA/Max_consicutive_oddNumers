import java.util.*;
public class Main {
    public static void main(String args[]) {
        int arr[] = {1,2,34,3,4,5,7,23,12};
        for(int i = 0;i<arr.length;i++) {
            if(arr[i]%2==1 && arr[i+1]%2==1 && arr[i+2]%2==1) {
                System.out.println(arr[i]+" "+arr[i+1]+" "+arr[i+2]);
            }
        }
    }
}
