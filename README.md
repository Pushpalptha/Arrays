# Arrays
public class Main{
    static int arr[]={45,67,89,345};
    static int largest()
    {
        int i;
        int max=arr[0];
        for(i=0;i<arr.length;i++){
            if(arr[i]>max)
                max=arr[i];
        }
        return max;
    }
    public static void main(String[] args){
        System.out.println("largest element in an array"+largest());
    }
}
                    (or)
public class Main {
    public static void main(String[] args) {
        int[] array = {45, 78, 23, 89};
        int target = 45;
        boolean isPresent = false;
        
        for (int i = 0; i < array.length; i++) {
            if (array[i] == target) {
                isPresent = true;
                break;
            }
        }
        
        if (isPresent) {
            System.out.println(target + " element is present");
        } else {
            System.out.println(target + " element is not present");
        }
    }
}

