## 自用一键脚本集合
#### nginx+h5ai+tls
```markdown
wget -N --no-check-certificate -q -O ws.sh "https://raw.githubusercontent.com/huahsui/tcp-xtls/gh-pages/ws-tls.sh" && chmod +x ws.sh && bash ws.sh
```
#### nginx+h5ai+vision
```markdown
wget -N --no-check-certificate -q -O xtls.sh "https://raw.githubusercontent.com/huahsui/sni-h5ai-xtls/main/sni%2Bxtls.sh" && chmod +x vision.sh && bash vision.sh
```
#### vision+reality (先行版)
```markdown
wget -N --no-check-certificate -q -O reality.sh "https://raw.githubusercontent.com/huahsui/tcp-xtls/gh-pages/reality.sh" && chmod +x reality.sh && bash reality.sh
```
#### nginx+reality (自己偷自己)
```markdown
wget -N --no-check-certificate -q -O reality.sh "https://raw.githubusercontent.com/huahsui/sni-h5ai-xtls/main/reality.sh" && chmod +x reality.sh && bash reality.sh
```
### v2rayN使用新版内核和自定义配置
https://github.com/2dust/v2rayN/releases/download/5.39/v2rayN.zip

https://github.com/huahsui/tcp-xtls/blob/gh-pages/Xray-windows-64.zip

1、先下载以上内核和v2rayN,然后解压v2rayN,并把Xray-windows-64压缩包里的文件复制进v2rayN文件夹。

2、打开v2rayN.exe,左上角依次选择  服务器 ——> 添加自定义配置服务器 ——> 浏览（打开客户端配置)  ——>  core类型（选xray） ——> 确定


