#ใบงานที่ 5
##เรื่อง การใช้งานคำสั่ง Console.WriteLine()
##วัตถุประสงค์
1). เพื่อให้นักศึกษาบอกวิธีการใช้คำสั่งแสดงผลบน Text Mode ในภาษา C# ได้
2). เพื่อให้นักศึกษาสามารถปรับแต่งคำสั่งแสดงผลทางหน้าจอตามต้องการได้

บันทึกผลการทดลอง

 หลังจากรันโปรแกรมผลที่ได้เป็นไปตามรูปด้านล่าง
 
 ![](https://github.com/est160/LAB-05/blob/master/img/lab%205.1.png?raw=true)
 
 เมื่อทำการแก้โปรแกรมตามรูปด้านล่างนี้
 
  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic2.png)

 และเมื่อทดสอบรันโปรแกรมผลที่ได้คือ
 
  ![](https://github.com/est160/LAB-05/blob/master/img/lab5.2.png?raw=true)



###คำถาม 5.1 เครื่องหมาย { }  ในคำสั่ง Console.WriteLine() มีลักษณะการใช้งานอย่างไร


  จากการทดลองจะเห็นว่าเลขในเครื่องหมาย {} นั้นอ้างอิงถึงตำแหน่งอาเรโดยเมื่อเราทำการเขียนโปรแกรมและทำการใส่ค่าอาเรและข้อมูลเช่น ("{0} and {1}.", 3, 6)
  
  
  ตัวเลข 3 และ 6 หลังเครื่องหมาย , จะถูกนำไปแทนที่ตำแหน่งอาเรที่เราได้กำหนดไว้ตามลำดับคือตำแหน่งที่ 0 และ 1
  
  
###คำถาม 5.2  ถ้ามีการใช้ตัวเลขใน { } ที่กระโดด เช่น {0} {2} {3} จะใช้งานได้หรือไม่ อย่างไร จงอธิบาย

 
  ไม่ได้ ดังรูป ![](https://github.com/est160/LAB-05/blob/master/img/lab%205.3.png?raw=true)
  
 
 2.5). แก้โปรแกรมตามรูปด้านล่างนี้
 

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic3.png)
  

 2.6). รันโปรแกรม และบันทึกผลที่ได้
 
 
ผลที่ได้หลังจากการทดลองรันโปรแกรมคือ ![](https://github.com/est160/LAB-05/blob/master/img/lab%205.4.png?raw=true)


3). ทดลองเรื่องการกำหนดความกว้างของอาร์กิวเมนต์

  3.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic4.png)

  3.2). รันโปรแกรม และบันทึกผลที่ได้


ผลที่ได้หลังจากการทดลองรันโปรแกรมคือ ![](https://github.com/est160/LAB-05/blob/master/img/lab%205.5.png?raw=true)


###คำถาม 5.3 การกำหนดความกว้างของอาร์กิวเมนต์ด้วยเครื่องหมาย { , }  ในคำสั่ง Console.WriteLine() มีรูปแบบการใช้งานอย่างไร

จะแสดงความกว้างของข้อความใน Console โดยเริ่มจากเลขทางซายเป็นหลักและมีความกว้างสูงสุดโดยดูจากเลขทางขวาของเครื่องหมาย , 


4). ทดลองเรื่องการกำหนดรูปแบบของอาร์กิวเมนต์

  4.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic5.png)

  4.2). รันโปรแกรม และบันทึกผลที่ได้


ผลที่ได้จากการรันโปรแกรมเป็นไปดังรูป คือ ![](https://github.com/est160/LAB-05/blob/master/img/lab%205.10.png?raw=true)


5). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของอาร์กิวเมนต์
  5.1). แก้โปรแกรมตามรูปด้านล่างนี้
 
 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic6.png)

  5.2). รันโปรแกรม และบันทึกผลที่ได้
  
ผลที่ได้จากการรันโปรแกรมเป็นไปดังรูป คือ ![](https://github.com/est160/LAB-05/blob/master/img/lab%205.9.png?raw=true) 

6). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของทศนิยมของอาร์กิวเมนต์
  6.1). แก้โปรแกรมตามรูปด้านล่างนี้

 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic7.png)

  6.2). รันโปรแกรม และบันทึกผลที่ได้
  
ผลที่ได้จากการรันโปรแกรมเป็นไปดังรูป คือ ![](https://github.com/est160/LAB-05/blob/master/img/lab%205.8.png?raw=true) 

## แบบฝึกหัด จงระบุ output ของบรรทัดคำสั่งต่อไปนี้

```csharp
1.  string name = "Hello";
    Console.WriteLine(String.Format("{0} there. I said {0}! {0}???", name));
2.    Console.WriteLine("{2:d} {0:d} {1:d}", 1, 2, 3);
3.    Console.WriteLine("Hello " + "World");
4.    Console.WriteLine("Here comes a slash \\");
5.    Console.WriteLine("|{0, 10}|", 999);
6.    Console.WriteLine("|{0,-10}|", 000);
7.    Console.WriteLine("The value: {0}.", 500);
8.    Console.WriteLine("The value: {0:C}.", 500);
9.    Console.WriteLine("{0,-10:F4}", 12.3456789);
10.   Console.WriteLine("{0,-10:C}", 12.3456789);
11.   Console.WriteLine("{0,-10:E3}", 12.3456789);
12.   Console.WriteLine("{0,-10:x}", 65535);
13.   Console.WriteLine("{0,-10:X}", 65535);
14.   int i; 
      Console.WriteLine("Value\tSquared\tCubed"); 
      for(i = 1; i < 10; i++) 
          Console.WriteLine("{0}\t{1}\t{2}", i, i*i, i*i*i); 
15.    Console.WriteLine("{0:#.###}.", 1234.56789);
```
