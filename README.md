# Pembuatan jaringan standar industri
# Student-Company
**Tentang**

Student company adalah perusahaan yang di buat dari nol oleh murid dan di jalankan oleh murid.
klien perusahaan kami meminta membuat jaringan dengan standar industri untuk perusahaan nya.
jadi divisi tkj melakukan simulasi full dengan Proxmox VE kami terbagi menjadi 3 tim
dan saya bagian dari tim sysadmin

**Studi Kasus**
> Sebuah perusahaan e-commerce skala menengah sering mengalami web server down karena trafik yang penuh. Mereka juga baru saja diretas sehingga data internalnya terancam. Bos perusahaan tersebut ingin agar (1) Website mereka tidak pernah down lagi meski banyak pengunjung, (2) Semua login karyawan diatur dari satu pusat dan punya kebijakan password yang ketat, dan (3) Semua serangan dari luar bisa dideteksi otomatis dan log-nya tersimpan di satu layar monitor khusus

**Job Description**
> Tim 1: Network & Perimeter (Infrastruktur Dasar)
> Tugas: Mengatur routing dasar, pembuatan segmentasi IP
> Fokus: Konfigurasi NAT dan Port Forwarding di Edge Firewall 
> 
> Tim 2: System Administrator
> Tugas DMZ: Instalasi dua Web Server (misal: Nginx/Apache) dan instalasi HAProxy. Memastikan load balancing berfungsi.
> Tugas Internal: Instalasi Windows Server untuk Active Directory, membuat user HR dan Finance, Join Domain untuk PC Client, dan menerapkan Password Policy via GPO.
> 
> Tim 3: Cyber Security / SOC
> Tugas: Instalasi mesin SIEM (Elastic/ELK Stack) dan IDS (Suricata).
> Fokus: Mengonfigurasi agar log dari traffic jaringan dan server bisa masuk dan terbaca di dashboard SIEM.

mengunakan
<img width="1600" height="702" alt="image" src="https://github.com/user-attachments/assets/ec6e1c6a-c35a-4eed-ba79-9c3bc2a151e0" />


proxmox 


<img width="365" height="181" alt="Sampul Portofolio Minimalis Fotosentris Hitam Putih (1)" src="https://github.com/user-attachments/assets/49b518b8-de63-49ea-b973-a559f5738e98" />


# tugas saya


- Membangun Active Directory domain corp.local di Windows Server 2022: OU HR & Finance, user hr01 & fin01.
- Join domain 2 client Windows 10; verifikasi login akun domain CORP\hr01 & CORP\fin01.
- Menerapkan GPO password policy (min. 8 karakter + complexity) dan wallpaper policy via shared folder; verifikasi dengan gpupdate /force.
- Bersama tim DMZ: pengujian load balancing round robin dan failover Virtual IP Keepalived.

<img width="362" height="236" alt="Sampul Portofolio Minimalis Fotosentris Hitam Putih (2)" src="https://github.com/user-attachments/assets/9f102914-2044-4534-89c6-2262e89ac448" />
<img width="358" height="181" alt="Sampul Portofolio Minimalis Fotosentris Hitam Putih" src="https://github.com/user-attachments/assets/d495d628-13cf-4f69-ab34-d38b41592c3d" />


buka file MoP(method of procedure) sysadmin more details




