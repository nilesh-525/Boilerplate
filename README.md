# Boilerplate
contains common code snippets. 

### Directions array
```java
int[][] dirs = {{0,1},{1,0},{0,-1},{-1,0}};

int[][] dirs = {{0,1},{1,1},{1,0},{1,-1},{0,-1},,{-1,-1},{-1,0},{-1,1}};
```
### Reverse array
```java
void reverse(int[] nums){
    int i = 0;
    int j = nums.length - 1;
    while(i < j){
        int temp = nums[i];
        nums[i] = nums[j];
        nums[j] = temp;
    }
}
```
