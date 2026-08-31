# Enumeracion NMAP

````
tarting Nmap 7.99 ( https://nmap.org ) at 2026-08-31 13:26 -0500
Nmap scan report for 10.130.177.206
Host is up (0.034s latency).
Not shown: 65531 closed tcp ports (reset)
PORT     STATE SERVICE    VERSION
22/tcp   open  ssh        OpenSSH 7.2p2 Ubuntu 4ubuntu2.8 (Ubuntu Linux; protocol 2.0)
| ssh-hostkey: 
|   2048 f3:c8:9f:0b:6a:c5:fe:95:54:0b:e9:e3:ba:93:db:7c (RSA)
|   256 dd:1a:09:f5:99:63:a3:43:0d:2d:90:d8:e3:e1:1f:b9 (ECDSA)
|_  256 48:d1:30:1b:38:6c:c6:53:ea:30:81:80:5d:0c:f1:05 (ED25519)
53/tcp   open  tcpwrapped
8009/tcp open  ajp13      Apache Jserv (Protocol v1.3)
| ajp-methods: 
|_  Supported methods: GET HEAD POST OPTIONS
8080/tcp open  http       Apache Tomcat 9.0.30
|_http-favicon: Apache Tomcat
|_http-open-proxy: Proxy might be redirecting requests
|_http-title: Apache Tomcat/9.0.30
No exact OS matches for host (If you know what OS is running on it, see https://nmap.org/submit/ ).
TCP/IP fingerprint:
OS:SCAN(V=7.99%E=4%D=8/31%OT=22%CT=1%CU=36709%PV=Y%DS=3%DC=I%G=Y%TM=6A95C76
OS:A%P=x86_64-pc-linux-gnu)SEQ(SP=101%GCD=1%ISR=10E%TI=Z%CI=I%II=I%TS=8)SEQ
OS:(SP=104%GCD=1%ISR=106%TI=Z%CI=I%II=I%TS=8)SEQ(SP=104%GCD=1%ISR=10D%TI=Z%
OS:CI=I%II=I%TS=8)SEQ(SP=105%GCD=1%ISR=105%TI=Z%CI=I%II=I%TS=8)OPS(O1=M4E8S
OS:T11NW7%O2=M4E8ST11NW7%O3=M4E8NNT11NW7%O4=M4E8ST11NW7%O5=M4E8ST11NW7%O6=M
OS:4E8ST11)WIN(W1=68DF%W2=68DF%W3=68DF%W4=68DF%W5=68DF%W6=68DF)ECN(R=Y%DF=Y
OS:%T=40%W=6903%O=M4E8NNSNW7%CC=Y%Q=)T1(R=Y%DF=Y%T=40%S=O%A=S+%F=AS%RD=0%Q=
OS:)T2(R=N)T3(R=N)T4(R=Y%DF=Y%T=40%W=0%S=A%A=Z%F=R%O=%RD=0%Q=)T5(R=Y%DF=Y%T
OS:=40%W=0%S=Z%A=S+%F=AR%O=%RD=0%Q=)T6(R=Y%DF=Y%T=40%W=0%S=A%A=Z%F=R%O=%RD=
OS:0%Q=)T7(R=Y%DF=Y%T=40%W=0%S=Z%A=S+%F=AR%O=%RD=0%Q=)U1(R=Y%DF=N%T=40%IPL=
OS:164%UN=0%RIPL=G%RID=G%RIPCK=G%RUCK=G%RUD=G)IE(R=Y%DFI=N%T=40%CD=S)

Network Distance: 3 hops
Service Info: OS: Linux; CPE: cpe:/o:linux:linux_kernel

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 33.64 seconds

````
Tomcat Vulnerable RCE

cve:
````
https://github.com/Hancheng-Lei/Hacking-Vulnerability-CVE-2020-1938-Ghostcat/blob/main/CVE-2020-1938.md

````

<img width="322" height="67" alt="image" src="https://github.com/user-attachments/assets/7837f5f9-2544-4529-a73e-bdbecbc74d8e" />


````
skyfuck:8730281lkjlkjdqlksalks
````
# Escalada

<img width="388" height="82" alt="image" src="https://github.com/user-attachments/assets/3cf7d87f-a59a-4834-b8ea-fe79126668dd" />


<img width="635" height="307" alt="image" src="https://github.com/user-attachments/assets/4fcb51e8-43e8-4cff-b5fc-0b0bb53b9664" />

<img width="639" height="199" alt="image" src="https://github.com/user-attachments/assets/7402e0de-2217-4570-852d-d118524e51f9" />

<img width="645" height="230" alt="image" src="https://github.com/user-attachments/assets/94542e74-cd75-4230-9050-a2452f101a6e" />

````
merlin:asuyusdoiuqoilkda312j31k2j123j1g23g12k3g12kj3gk12jg3k12j3kj123j

````
<img width="277" height="45" alt="image" src="https://github.com/user-attachments/assets/168a064e-664e-47f2-ad50-862ceed85e83" />

## Escalado root
<img width="638" height="125" alt="image" src="https://github.com/user-attachments/assets/5090df6b-70a6-42ca-a752-a93842c146cc" />

<img width="650" height="151" alt="image" src="https://github.com/user-attachments/assets/39e57177-2281-4c84-8874-68f250c97215" />
