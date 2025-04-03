🔥 วิธีรัน Playbook

ansible-playbook -i inventory/inventory.ini playbook.yml

📌 ข้อดีของโครงสร้างนี้
✅ สามารถติดตั้ง/ถอนการติดตั้งเฉพาะ role ได้ เช่น
ansible-playbook -i inventory/inventory.ini playbook.yml --tags "node"

ansible-playbook playbook.yml

ansible-playbook uninstall_playbook.yml

🚀 วิธีรัน Ansible แบบกำหนดค่าเอง
ถ้าต้องการเปลี่ยนเวอร์ชันขณะรัน สามารถใช้ --extra-vars (-e)

sh
คัดลอก
แก้ไข
ansible-playbook -i inventory/inventory.ini playbook.yml -e "node_version=20.5.1"