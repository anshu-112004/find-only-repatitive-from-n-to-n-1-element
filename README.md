# find-only-repatitive-from-n-to-n-1-element


// User function Template for Java
class Solution {
    public int findDuplicate(int[] arr) {
        // code here
      
        long n=arr.length,sum=0;
        for (int x:arr){
            sum+=x;
        }
        long c=n-1;
        long calculation=(c*(c+1))/2;
        return  (int)sum -(int)calculation;
    }

}
