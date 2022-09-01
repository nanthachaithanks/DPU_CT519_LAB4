# DPU_CT519_LAB4

วิธีการใช้งาน

sudo git clone https://github.com/nanthachaithanks/DPU_CT519_LAB4.git

cd dpu_ct519_Lab4

sudo docker-compose up -d

sudo docker exec -i db sh -c 'exec mysql -uroot -p"$MYSQL_ROOT_PASSWORD"' < mysql-backup/my_data_645162010011.sql

เข้า browser ใส่ ipเครื่อง vm
