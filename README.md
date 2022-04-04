# install chr di proxmox
how to install chr (mikrotik routeros chr) on proxmox
1. buat vm dari GUI seperti biasa (contoh: vm-104)
2. hapus disk 104 dari menu hardware
3. masuk shell terminal proxmox
4. cd /download
5. download chr terbaru
6. unzip chr
7. import dgn cara :
```bash
qm importdisk 104 chr-7.1.5.img local-lvm
```
8. tambahkan / attach disk
9. atur boot-up
10. selesai
