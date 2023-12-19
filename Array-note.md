#二分查找
二分法使用条件： 1.数组为有序数组 2.数组中无重复元素
##怎么输入一个未知长度的int型数组
Scanner scan = new Scanner(System.in);
String[] intList = scan.nextLine().split(" ");
int[] nums = new int[intList.length];
for (int i = 0; i < intList.length; i++) {
    nums[i] = Integer.parseInt(intList[i]);
}
Arrays.toString 将数组转化为字符串打印输出


