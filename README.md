# NewWorld-For-DirectAdmin-Login-Page
登录后退出 返回页

```html
<input type="hidden" value="http://www.elinkhost.com" name="LOGOUT_URL"/>
```
修改为您的网址

 #### 登陆界面安装 ####
 
 ```sh
cd /usr/local/directadmin/data/templates #进入主题所在目录
wget https://github.com/ydidc/NeWorld-For-DirectAdmin-Login-Page/archive/master.zip #下载NewWorld主题模版压缩包
unzip master.zip #解压缩主题压缩包
rm custom -rf
rm login_images -rf
mv NeWorld-For-DirectAdmin-Login-Page-master/* ./ #修改主题文件夹名称
rm -f master.zip #删除主题模版压缩包
chown -R diradmin:diradmin ./* #设置主题所有权
 ```
