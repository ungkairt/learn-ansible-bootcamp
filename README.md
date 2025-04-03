🔥 วิธีรัน Playbook

ansible-playbook -i inventory/inventory.ini playbook.yml

📌 ข้อดีของโครงสร้างนี้
✅ สามารถติดตั้ง/ถอนการติดตั้งเฉพาะ role ได้ เช่น
ansible-playbook -i inventory/inventory.ini playbook.yml --tags "node"

ansible-playbook playbook.yml

ansible-playbook uninstall_playbook.yml