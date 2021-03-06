# HW1 计算机基础

1. 根据<https://www.gnu.org/>，GNU是'GNU's Not Unix'的递归首字母缩写词。GNU最初是一个运动(Free Software Movement)，以抗衡Unix的操作系统收费。1984年1月，GNU工程开始实施，以创建一个类Unix操作系统。

   类Unix操作系统中用于分配资源和硬件管理的程序成为“内核”。GNU使用的典型内核是Linux，由Linus开发。该组合称为GNU/Linux操作系统。我们现在安装的Linux实际上都是GNU/Linux操作系统。

   常见的操作系统有Windows，Linux，iOS，Android等。比较常见的编程语言有C/C++，JAVA，python等。   

2. 要表示四种碱基，最少需要两位二进制数。例如可以用00表示A，01表示C，10表示C，11表示G。如果要表示20种氨基酸，需要
   $$
   \lceil \log _220\rceil=5
   $$
   种碱基。  

3. $$
   (235)_{10}=(11101011)_2=(353)_8=(EB)_{16}\\
   (62)_{10}=(111110)_2=(76)_8=(3E)_{16}\\
   (223)_{10}=(11011111)_2=(337)_8=(DF)_{16}
   $$

4. $$
   Q=33-10\log P\\
   P=10^{\frac{33-Q}{10}}\\
   其中，Q为转换后字符的ASCII码值
   $$

   | 字符 | Q    | P       |
   | ---- | ---- | ------- |
   | C    | 67   | 3.98e-4 |
   | :    | 58   | 3.16e-3 |
   | )    | 41   | 0.158   |
   | ?    | 63   | 0.001   |
   | 7    | 55   | 6.31e-3 |

   $$
   P=\prod\limits_{i=1}^5\left(1-P_i\right)=0.834
   $$

5. 浮点数在计算机中表示时采用IEEE 754标准，首先需要将十进制的浮点数表示为二进制的形式。然而大多数十进制浮点数转化为二进制形式时，小数部分会出现无限循环。而单精度浮点数和多精度浮点数对于尾数都有一些限制，溢出部分会直接舍去。因此大部分浮点数在计算机内不能被精确表示。

6. $$
   (13.1)_{10}=(1.10100011001100110011001\cdots)\times 2^3\\
   该浮点数表示为0 10000010 10100011001100110011001
   $$

   $$
   (0.65)_{10}=(1.01001100110011001100110\cdots)\times 2^{-1}\\
   该浮点数表示为0 01111110 01001100110011001100110
   $$

7. 8位二进制补码表示的最大整数为127=0b01111111，最小整数为-128=0b11111111。

8. 1010表示十进制-6，其原码10000110，补码11111010；011001表示十进制25，其源码与补码都是00011001；1111111000表示十进制-8，其原码10001000，补码11111000；01补码00000001。

9. 网络地址：(11000000.10101000.00000101.01100100) and (11111111.11111111.10000000.00000000)=(11000000.10101000.00000000.00000000)->(192.168.0.0)

   主机数还有15位可用，将网络地址后15位置1，得到广播地址(192.168.127.255)

   由于最后一段不能为0或255，则网段为(192.168.0.1)-(192.168.127.254)。

10. 网上下载centOS 7的iso镜像和VMware虚拟机。按照步骤在虚拟机内配置并安装系统即可。

    LSB Version:	:core-4.1-amd64:core-4.1-noarch:cxx-4.1-amd64:cxx-4.1-noarch:desktop-4.1-amd64:desktop-4.1-noarch:languages-4.1-amd64:languages-4.1-noarch:printing-4.1-amd64:printing-4.1-noarch
    Distributor ID:	CentOS
    Description:	CentOS Linux release 7.9.2009 (Core)
    Release:	7.9.2009
    Codename:	Core



