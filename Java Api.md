## Java Api

#### Int

##### 进制转换

| 10进制转化其他进制 | 对应的方法,参数:n(原10进制数据),r(进制), | 返回值       |
| ---------- | -------------------------- | --------- |
| 10进制转2进制   | Integer.toBinaryString(n); | 一个二进制字符串. |
| 10进制转8进制   | Integer.toOctalString(n);  | 一个八进制字符串  |
| 10进制转16进制  | Integer.toHexString(n);    | 一个16进制字符串 |
| 10进制转 r 进制 | Integer.toString(100, 16); | 一个r进制字符串  |



#### 数组

数组排序: Arrays.sort(char[]);
数组查询指定内容: Arrays.binarySearch(int[], int)
数组copy: System.arraycopy(arrayfrom, 0, arrayto, 0, length);
数组转String：Arrays.toString(arrays1)

#### String

字符串转char数组: string1.toCharArray()
String判断相同: string1.equals(string2)

int/char转String: int/char + ""

#### BigInterge

创建大数: BigInterger.valueof(int1)
大数次方操作: bigInterger1.pow(Int)
大数取模: bigInterger1.mod(bigInterger2)
大数转int: bigInterger1.intValue()

#### StringBuilder

创建StringBuilder: new StringBuilder(String1)
反转StringBuilder: stringBuilder1.reverse()
StringBuilder转String: stringBuilder1.toString()

#### Scanner

Scanner sc = new Scanner (new BufferedInputStream(System.in))
Scanner sc = new Scanner (System.in); 在读入数据量大的情况下，上面的速度会快些。
读一个整数： int n = sc.nextInt(); 
读一个字符串：String s = sc.next(); 
读一个浮点数：double t = sc.nextDouble(); 
读一整行： String s = sc.nextLine(); 
判断是否有下一个输入可以用sc.hasNext()或sc.hasNextInt()或sc.hasNextDouble()或sc.hasNextLine()

#### printf

##### %d

%d: 正常输出

%Yd: 输出Y位，不足Y位在前面补空格，如果大于Y位，正常输出

%XYd: 输出Y位，不足Y位在前面补X，如果大于Y位，正常输出





#### 超时

1. 除法尽量避免多次除

2. 有位数要求且需要补数一律用（例：System.out.println(String.format("%02d:%02d:%02d",h,m,s));）




