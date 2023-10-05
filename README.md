# CNY_Exchange_Rate_Finder.ipynb
## ติดตามสถานะอัตราแลกเปลี่ยนจากเว็บไซต์นำเข้าจากจีน
Objectives : อัตราแลกเปลี่ยนของแต่ละเว็บไซต์ในแต่ละวันมีแนวโน้มเปลี่ยนแปลงบ่อยในแต่ละวัน ต้องใช้หลายขั้นตอนในการติดตามอัตราค่าขนส่งเพื่อติดตามและนำมาวิเคราะห์

**Brand**
- Ariyaya
- Plm-cargo
- Weshopchina
- Yd-cargo
- Uneedcargo
- Jmfcargo
- Ptcargo

โดยให้เก็บอัตราแลกเปลี่ยน ณ วันเวลาที่ดึง โดยให้เก็บ Timestamp วันเวลามาด้วย
หลังจากดึงข้อมูลแล้วให้เก็บข้อมูลไว้ที่ CNY.exchange.rate.txt และส่งต่อไปยัง line notify โดย ณ ตอนนี้จะดึงข้อมูลในช่วงเช้าและเย็นของทุกวันเพื่อเก็บข้อมูลนำมาทำเป็น Time series Analysis ต่อไป
