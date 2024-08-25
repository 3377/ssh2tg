# 效果图
![image](https://github.com/user-attachments/assets/05fc40b7-6234-45ac-9dbd-366acc49445f)

# 登录机器执行命令
curl -s -o /etc/profile.d/ssh2tg.sh https://raw.githubusercontent.com/3377/ssh2tg/main/ssh2tg.sh && chmod +x /etc/profile.d/ssh2tg.sh && sed -i 's/replacetoken/替换为你的tg机器人token/g;s/replaceid/替换为你的tg用户ID/g' /etc/profile.d/ssh2tg.sh

