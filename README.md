# VPS配置一键脚本
> 自用
## 使用

```bash
apt update && apt upgrade
apt install p7zip vim 
mkdir .ssh
echo 'ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIOOGBMAl2vE63UYNXq34wCtZSCNIJlS+wCzGLM3Gc3+X' >> .ssh/authorized_keys
echo 'ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIB/8HND6TZyJ0O5SeYmM94scroscIH39hB5J6qbvTXZD' >> .ssh/authorized_keys
wget -O ss-rust.sh --no-check-certificate https://raw.githubusercontent.com/1235467/tw-config/master/ss-rust.sh && chmod +x ss-rust.sh && ./ss-rust.sh
```
