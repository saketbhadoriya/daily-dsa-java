class Solution {
    public void sortColors(int[] nums) {
        int n = nums.length;
        int i, j, temp;
        boolean swapped;
        for (i = 0; i < n - 1; i++) {
            swapped = false;
            for (j = 0; j < n - i - 1; j++) {
                if (nums[j] > nums[j + 1]) {
                    

                    temp = nums[j];
                    nums[j] = nums[j + 1];
                    nums[j + 1] = temp;
                    swapped = true;
                }
            } 
        }
    }
}


//simple code using arraylist
class Solution {
    public void sortColors(int[] nums) {
        int n = nums.length;
        ArrayList<Integer> a = new ArrayList<>();
        ArrayList<Integer> b = new ArrayList<>();
        ArrayList<Integer> c = new ArrayList<>();
        for(int i=0;i<n;i++){
            if(nums[i]  == 0){
                a.add(nums[i]);
            }
            if(nums[i] == 1){
                b.add(nums[i]);
            }
            if(nums[i]== 2){
                c.add(nums[i]);
            }
        }
         a.addAll(b);
        a.addAll(c);
    for(int i = 0;i<a.size();i++){
         nums[i] = a.get(i);
    }
    }
}
