下载，安装
wget -O anytls-install.sh https://raw.githubusercontent.com/xu348025782/anytls-install/main/anytls-install

赋予执行权限：
chmod +x anytls-install.sh

执行安装（按提示输入端口和密码）：
sudo ./anytls-install.sh install

【常用管理命令】
  安装/更新: sudo ./anytls_manager.sh install
  卸载服务  : sudo ./anytls_manager.sh uninstall
  启动服务  : sudo ./anytls_manager.sh start
  停止服务  : sudo ./anytls_manager.sh stop
  重启服务  : sudo ./anytls_manager.sh restart
  服务状态  : ./anytls_manager.sh status
  查看日志  : ./anytls_manager.sh log (可加参数如 -n 50)
  显示二维码: ./anytls_manager.sh qr
  查看帮助  : ./anytls_manager.sh help
