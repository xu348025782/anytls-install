下载，安装

wget -O anytls_manager.sh https://raw.githubusercontent.com/xu348025782/anytls-install/main/anytls-install && chmod +x anytls_manager.sh && sudo ./anytls_manager.sh install

执行安装（按提示输入端口和密码）：

安装完成后，你只需要通过 ./anytls_manager.sh 配合不同的参数即可管理服务：

功能描述执行命令查看管理菜单./anytls_manager.sh

查看运行状态./anytls_manager.sh status

重新显示二维码./anytls_manager.sh qr

查看实时日志./anytls_manager.sh log

重启服务sudo ./anytls_manager.sh restart

停止服务sudo ./anytls_manager.sh stop

启动服务sudo ./anytls_manager.sh start

彻底卸载sudo ./anytls_manager.sh uninstall
  
