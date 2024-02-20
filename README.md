# rhevtoospmigration


Rhev platformundan openstack platformuna migration çalışması hakkında ansible playbook hazırlanmıştır.


Bu çalışma ile Rhevde çalışan VMler sanal makine aracılığı ile OSP ortamına migrate edilir ve OSP üzerinde instance olarak ayağa kaldırılır.

Çalışma esnasında default bir vm kurulur, rhev ve ospde bulunan ortak vlanlardan makineye subnet tanımı yapılır. Sonrasında ansible ve pyhton paketleri bu makine üzerine deploy edilir.

Sonrasında ise ansible playbook çalıştırılarak makine kapatılır sonrasında sanal makine üzerinden  OSP'ye aktarılır. 



