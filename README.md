# Project 1: Enterprise Network Infrastructure Design & Implementation (Simulation)



## - Objective: ออกแบบและจำลองระบบเครือข่ายสำหรับองค์กรขนาดกลางที่มี 3 แผนก (HR, IT, Sales) และ 1 สาขาย่อย

##- Technologies Used: Cisco Packet Tracer / GNS3, Cisco IOS, VLANs, OSPF, NAT, ACLs

### - Key Responsibilities:
```bash
   - Network Segmentation: ออกแบบและคอนฟิก VLANs และ Inter-VLAN Routing (Router-on-a-Stick) เพื่อแยก Traffic ของแต่ละแผนกออกจากกันเพื่อความปลอดภัย

   - Dynamic Routing: คอนฟิกโปรโตคอล OSPF เพื่อให้ Router สำนักงานหลักและสาขาสามารถแลกเปลี่ยนเส้นทาง (Routing Table) ได้อย่างอัตโนมัติ

   - Security & Access Control: ใช้ Standard/Extended ACLs เพื่อจำกัดสิทธิ์การเข้าถึง Server ส่วนกลาง (เช่น แผนก Sales เข้าถึง Server ของ IT ไม่ได้)

   - Internet Connectivity: คอนฟิก Static NAT/PAT เพื่อให้อุปกรณ์ภายในเครือข่ายสามารถออกสู่อินเทอร์เน็ตได้โดยใช้ Public IP เพียงเบอร์เดียว
```
## - Outcome: ระบบเครือข่ายสามารถทำงานได้อย่างสมบูรณ์ มีการจัดการ Traffic ที่เป็นระเบียบ และรองรับการขยายตัวในอนาคต (Scalability)

