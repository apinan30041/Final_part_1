คำตอบ
1.agile  ไม่ได้หมายถึงพวก  hacker  แต่มันคือการทำตามคำสั่งของลูกค้า  ถ้าลูกค้าสั่งอะไรมาเราก็แค่ทำตามที่ลูกค้าสั่งเท่านั้นส่วน  
waterfall  เป็นการพัฒนาระบบซอฟต์แวร์แบบขั้นบันได หรือน้ำตก คือลูกค้าอยากได้อะไรในระบบเราก็แค่ทำตามที่ลูกค้าสั่งมาเป็นขั้นตอน  เ
มื่อระบบเสร็จแล้วก็จะทำการอบรม สอนใช้ระบบก่อนส่งมอบระบบให้กับลูกค้า

2.ไม่เป็นความจริง คือ git หรือ github นี้ สามารถเปลี่ยนชื่อไฟล์ได้ แค่ cvs และ svn ไม่สามารถเปลี่ยนชื่อไฟล์ได้ก็จริงอยู่ 
แต่ในบางบริษัทก็ยังยึดติดกับระบบเก่าอยู่ ทำให้ cvs และ svn นี้ยังไม่สูญพันธุ์

3………..

4.หากเกิด conflict ในการ merge นั้น ก็แสดงว่า มีการแก้ไข  source code ที่มีการซ้อนทับกัน  แต่ถ้า merge แล้วไม่เกิด conflict ขึ้น 
แสดงว่า source code ที่มีการแก้ไขไม่มีการซ้อนทับกัน

5. abcde"a".."e"
 

6. web application ส่วนใหญ่แล้วจะใช้ได้ฟรี ไม่เสียค่าใช้จ่าย แต่หากเป็นซอฟต์แวร์ ที่มาในรูปแบบ CD แล้วต้องถูกกฎหมายเท่านั้น 
เพราะฉะนั้น จะต้องเสียค่าใช้จ่ายในการซื้อซอฟต์แวร์ที่ถูกกฎหมาย


7.
  1.เบราว์เซอร์ที่ออกการร้องขอสำหรับ URL /users ด้วยเช่น
  2.Rails routes  /users ด้วยเช่นเส้นทางดำเนินการ Index ในตัวควบคุมผู้ใช้
  3.การดำเนินการ Index ถามแบบผู้ใช้ในการดึงข้อมูลผู้ใช้ทั้งหมด (User.all)
  4.แบบจำลองผู้ใช้ดึงจากฐานข้อมูลผู้ใช้
  5.รูปแบบผู้ใช้ส่งกลับรายการของผู้ใช้ตัวควบคุม
  6.ตัวควบคุมจับผู้ใช้ในตัวแปร @users ซึ่งจะถูกส่งผ่านไปยังมุมมอง Index
  7.มุมมองใช้ ruby ในการแสดงหน้าเป็น HTML
  8.ตัวควบคุมผ่าน HTML กลับไป browser.5
8. Front-End Framework คือ ชุดโค้ดที่ช่วยให้นักพัฒนาส่วน Front-End ทำงานได้สะดวกขึ้น โดยจะรวบรวมโค้ด 
HTML / CSS สำเร็จรูปในการวาง Layout, ตัวอักษร, ปุ่ม, เมนูบาร์ ฯลฯ มาให้เรียบร้อย โดยหน้าที่ของเราคือแค่ก็อปโค้ดส่วนที่เราต้องการไปใช้ได้เลย
ข้อดีคือ เนื่องจาดมันมาเป็นชุด code มาให้อยู่แล้ว เราก็นำไปใช้ได้เลย
ข้อเสียคือ จะไม่มีรูปแบบของ mvc  จึงทำให้เกิดปัญหาในการแก้ไขงานมากกว่า

9.
- เป็น Platform as a Service (Paas) ที่ให้เราใช้งานได้ฟรี (มีแบบเสียเงินด้วย) โดยรองรับภาษาโปรแกรมที่หลากหลาย เช่น Ruby, PHP, Node.js, Python, Java, Clojure, Scala และยังสามารถสร้าง buildpack สำหรับภาษาอื่นๆได้ เช่น Lua ที่รันอยู่บน OpenResty ได้อีกด้วย
- บทบาทคือ เหมาะกับบุคคลทั่วไป ที่สนใจในการสร้าง Web application โดยใช้  PHP จึงทำให้การเขียนเว็ปนั้น มีคนที่สนใจที่จะเข้ามาสร้างเว็ปของตัวเอง จึงทำให้วงการเว็ปนี้ได้พัฒนาไปอีกขั้น
10.เพราะในปัจจุบัน โลกของเรามันก้าวไกลมาก เรื่องเว็ป การเขียนเว็ป สื่อการเรียนการสอนผ่าน0เว๊ป จึงทำให้เว็บไซต์บนโลกอินเทอเน็ตมีการเคลื่อนไหวไปในทางการศึกษาหาความรู้ซะส่วนใหญ่ ดังนั้นวิชานี้จะช่วยให้เราได้ทันโลกมากขึ้น เพราะเราจะได้รู้ถึงการพัฒนาของเว็บไซต์ต่างๆ การเขียนโปรแกรม ภาษาที่ใช้ที่เข้ามาใหม่ๆ
