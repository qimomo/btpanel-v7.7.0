# btpanel-v7.7.0 备份
## 降级

```
wget https://raw.githubusercontent.com/qimomo/btpanel-v7.7.0/main/install/src/LinuxPanel-7.7.0.zip
unzip LinuxPanel-*
cd panel
bash update.sh
cd .. && rm -f LinuxPanel-*.zip && rm -rf panel
```
## 删除手机验证

```
rm -f /www/server/panel/data/bind.pl
```
# 直接安装
```
curl -sSO https://raw.githubusercontent.com/qimomo/btpanel-v7.7.0/main/install/install_panel.sh && bash install_panel.sh
```
