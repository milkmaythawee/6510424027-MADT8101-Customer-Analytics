Project : Lead System
![CDP Design](https://github.com/milkmaythawee/6510424027-MADT8101-Customer-Analytics/assets/140238319/dbc98a93-07a5-42c5-ba8d-c9d8472e0e4b)

The Lead system consists of a customer data platfrom, data management platform and customer relation ship

1. DMP : Data management platform​
    - หา Lookalike Audiences ที่หน้าตาคล้ายกับ 1st Party Data ที่เรามี เทียบกับ 3rd Party Data ในตลาด เพื่อขยายฐาน Target Audiences ให้กว้างขึ้นและตรงตามกลุ่ม Target มากที่สุด
    - สร้าง Buyer Persona สำหรับทำ Targeting โดย Marketers จะเป็นคนเลือกกลุ่มลูกค้าที่ผ่านการทำ Segmentation มาเรียบร้อยแล้วว่าแบ่งออกเป็นกลุ่มไหนบ้าง ยกตัวอย่างง่าย ๆ ว่า เราอยากได้คนที่บินไปเชียงใหม่ทุก ๆ เดือนเป็นประจำ เราก็เพียงแค่เลือก Segments ที่เราต้องการ หลังจากนั้น DMP จะส่งฐานข้อมูลลูกค้าโดยใช้ Annonymous Identity (Devices-ID or Cokkies-ID)ให้กับผู้ให้บริการซื้อ Media หรือในวงการโฆษณาเรารู้จักกันดีในชื่อ Demand Side Platform (DSP) ไปหาคนกลุ่มนี้แสดงโฆษณา ซึ่งกระบวนการทั้งหมดนี้จะวนลูปซ้ำ ๆ ไปเรื่อย ๆ แบบ Real-time เมื่อมีข้อมูลใหม่เข้ามา DMP ก็จะทำการ Segmentation เพื่อแบ่งกลุ่มและส่งข้อมูลลูกค้าที่ไม่ได้ระบุตัวตน ตาม Attributes ที่เราเลือกไว้ ให้ DSP แสดงโฆษณา ทำแบบนี้ไปเรื่อย ๆ
    - Personalize เนื้อหาให้กับโฆษณาหรือเว็บไซต์ DMP จะทำการเรียนรู้ว่าคนกลุ่มไหนต้องแสดง Creatives แบบไหนเพื่อทำให้เขาสนใจ ประโยชน์จากการที่ DMP ทำงานบนพื้นฐานของข้อมูลที่ไม่ระบุตัวตน ทำให้เราสามารถใช้ DMP optimize funnel ใน stage ของการหาลูกค้าใหม่ (Acquisition) ได้ ยกตัวอย่างเช่น เราเป็นคนที่เข้าเว็บไซต์ขายของชื่อดังเจ้าหนึ่ง เว็บไซต์ไม่รู้ว่าเราเป็นใคร แต่เว็บไซต์รู้พฤติกรรมพื้นฐานของเราจาก Devices-ID หรือ Cookies-ID ซึ่ง DMP จะทำการเอาข้อมูลเหล่านั้นไปทำ Segmentation เพื่อหาว่าเราเป็นคนกลุ่มไหน ควรที่จะเสิร์ฟ Content แบบไหนให้เรา เมื่อรู้แล้ว DMP จะติดต่อกับเว็บไซต์ หรือในทางการตลาดเราเรียกกันว่า Digital Personalization Engine (DPE) เพื่อให้ DPE ไปปรับ Content ในหน้าเว็บไซต์ให้ตอบโจทย์เรามากขึ้น กว่า Content ปกติ
  *DMP : Data management platform​ ใน Lead System ได้แก่ข้อมูลจาก Facebook Pixel, Facebook Business Manager, Google Ads, Google Analytics, Ecommerce Platform

2. CDP : Customer data platform
    - Data Collection - รวมรวมข้อมูลจากทุก Channels ที่ประกอบไปด้วยข้อมูลที่ระบุตัวตนได้ เราเรียกข้อมูลพวกนี้ว่า Personally Identifiable Information (PII) ซึ่งแตกต่างจาก DMP ที่เป็น Annonymous สิ่งนี้จะทำให้เรามีข้อมูลที่ถาวรกว่า DMP เพราะว่า Annonymous data ที่อยู่ใน DMP จะมี lifecycle ที่สั้น อยู่ได้ไม่นาน
    - Profile Unification - จะทำการรวมศูนย์ข้อมูล Individual ของแต่ละคนจากหลากหลาย Sources สร้างให้เกิด 360 Degree Customer Profile เพื่อให้เราเห็นและเข้าใจในทุก ๆ มุมมองของลูกค้า
    - Segmentation - จะทำการจัดกลุ่มลูกค้าเหมือนกับที่ DMP ทำแต่ CDP จะมี Information ในการทำ Segments ที่มากกว่า เพราะใช้ PII เข้ามาช่วย
    - Activation - จังหวะนี้คือความฝันสูงสุดของนักการตลาดทุกคน คือเอาข้อมูลที่ผ่านการวิเคราะห์แล้วไปใช้ ซึ่งเราสามารถเอาไปใช้ประโยชน์ได้หลากหลายมาก ไม่ว่าจะเป็น
    - Next-best Recommendations: ทำนายเพื่อหา Offer ที่เหมาะสมกับลูกค้าเพื่อให้เกิดผลลัพธ์ของ Campaign ที่ดีขึ้น
    - Dynamic Creative Optimization: ใช้ Data ในการประเมินว่าควรแสดง Content หรือ Artwork แบบไหนให้ตรงความต้องการลูกค้าและช่วงเวลาที่เหมาะสม
    - Testing and Self-operation: ใช้ทำ A/B Testing และ Multivariate Testing เพื่อทดสอบผลลัพธ์จากการทำ Campaigns
    - Real-time Decisions: ใช้เป็นเครื่องมือในการตัดสินใจเพื่อปรับ Campaign Attributes แบบ Real-time เพื่อให้เกิดผลลัพธ์สูงสุด
    - Journey Analytics and Discovery: เพื่อวิเคราะห์และประเมินภาพรวมของ Campaign
    - ซึ่งกระบวนการนี้ก็จะต้องไปเชื่อมต่อกับ Platform ที่หลากหลายไม่ว่าจะเป็น Digital Experience Platform (DXP) ในการเอาไปปรับ Content หรือ Campaign ที่กำลังรันอยู่ หรือเชื่อมกับ Marketing Dashboards เพื่อแสดงผลออกมาใช้ในการวิเคราะห์ข้อมูลสำหรับการวางแผนและรายงานผล และอื่น ๆ อีกมาก ซึ่งจะมาเหล่าให้ฟังในโอกาสต่อ ๆ ไป
   *CDP : Customer data platform​​ ใน Lead System ได้แก่ข้อมูลที่ได้ถูกวิเคราะห์จาก DMP มาเรียบร้อยแล้ว ในขั้นตอนนี้สามารถทำ Segmentation ในโมเดลของ ML ได้เช่น RFM, Churn Prediction

3. CRM : Customer relation management​
       ใน Lead System ได้แก่ข้อมูลที่ได้ถูกวิเคราะห์จาก DMP หรือ CDP มาเรียบร้อยแล้วซึ่งจะเป็นการใช้ Email SMS หรือ การรันโฆษณาผ่านแฟลตฟอร์ม  ซึ่งขั้นกว่าของการทำ CRM คือการทำ Marketing Automation (MAP) เป็นการตลาดแบบอัตโนมัติด้วยการใช้ซอฟต์แวร์หรือเทคโนโลยีมาเป็นเครื่องมือเพื่อทำกิจกรรม ทางการตลาดโดยอัตโนมัติ ช่วยวิเคราะห์พฤติกรรมของลูกค้า เข้าใจถึงความต้องการของลูกค้าได้ตรงจุด เช่น การตลาด ผ่านอีเมล การโพสต์โซเชียลมีเดีย และแม้กระทั่งแคมเปญโฆษณา เพื่อเพิ่มประสิทธิภาพ มอบประสบการณ์ที่เป็นส่วนตัว ให้กับลูกค้าด้วยการใช้เทคโนโลยีการตลาดอัตโนมัติเหล่านี้มาช่วยให้การทำงานนั้นง่ายและรวดเร็วขึ้น
