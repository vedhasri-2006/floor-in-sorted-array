# floor-in-sorted-array
static int findFloor(int[] arr, int x) {
     write code here
    int count=0;
    if(arr[0]>x){
        return -1;
    }
    for(int i=0;i<arr.length;i++){
        if(arr[i]<=x){
            count++;
        }
    }
    count--;
    return count;
}
