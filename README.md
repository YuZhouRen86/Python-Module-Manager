Introduction  介绍
============

**Python Module Manager** provides an efficient solution for deploying Python modules. You can easily install, uninstall and update modules using this program without having to input commands in the terminal window.  
**Python模块管理**提供了一种高效的部署 Python 模块的方案，您可使用本程序轻松地安装、卸载、更新模块，无需在终端窗口输入命令。

If Python is already installed on your system, the program will automatically recognize them, just select the required version in the drop-down box and click "**OK**". If you are using **Embedded Python**, select the "**Custom**" option in the drop-down box and **input root directory of Python** on the right side, click "**OK**".  
In the "**Manage Modules**" interface, all the installed modules will be listed, you can install the required modules, or uninstall and switch versions.  
In the "**Batch Management**" interface, you can install or uninstall multiple modules in a single step. Select install or uninstall in the drop-down box, input the modules you want to process in the right side, **separate the modules by spaces and use "==" for the version number**. Example: "**urllib3 pyglet==1.5.18**".

如果 Python 已安装到系统，本程序将自动识别它们，只需在下拉框中选择所需版本，点击“**确定**”即可。如果您使用 **Embedded Python**，请在下拉框中选择“**自定义**”选项，并在右侧**输入 Python 根目录**，点击“**确定**”。  
在“**管理模块**”界面，所有已安装的模块将被列出，您可以安装所需模块，或者卸载、切换版本。  
在“**批量管理**”界面，您可以通过一步操作安装或卸载多个模块。在下拉框中选择安装或卸载，在右侧输入要操作的模块，**模块间以空格分割，使用“==”表示版本号**。示例：“**urllib3 pyglet==1.5.18**”。

**The program relies on pip to work**. If pip is not installed correctly, the program will automatically jump to the "**Configure pip**" interface, click "**OK**" to download and install it. You can also install a specific version of pip. For **Embedded Python**, **follow the prompt to complete the additional steps** after installing pip.  
**本程序依赖 pip 运作**。pip 未正确安装时，本程序将自动跳转到“**配置pip**”界面，点击“**确定**”下载并安装它。您也可以安装指定版本的 pip 。对于 **Embedded Python**，在安装 pip 后，请**按照提示完成额外操作**。

The program automatically selects an index based on your system's region settings to make installation faster. You can also select it manually.  
本程序根据系统区域设置自动选择索引，使安装更快速。您也可以手动选择。

FAQ  常见问题
===

**Q: Which Python versions are supported?**  
**问：哪些 Python 版本受支持？**

**A**: Python Module Manager supports Python 2.6, 3.1 and above.  
**答**：Python模块管理支持 Python 2.6、3.1 以上版本。

**Q: Which Python distributions are supported?**  
**问：哪些 Python 发行版受支持？**

**A**: CPython and PyPy are supported, other distributions are not.  
**答**：CPython 和 PyPy 受支持，其他发行版暂不支持。

**Q: What is the difference between the Microsoft Store version and the regular version?**  
**问：Microsoft Store 版本和普通版本有什么区别？**

**A**: The Microsoft Store version supports automatic updates, while the regular version requires you to download the update manually.  
**答**：Microsoft Store 版本支持自动更新，普通版本则需手动下载更新。

**Q: Encountered the error "PermissionError: [WinError 5] Access denied.", how to solve?**  
**问：遇到“PermissionError: [WinError 5] 拒绝访问。”的报错，该如何解决？**

**A**: Permissions error, usually caused by running the program as a non-administrator when Python version 3.5 or higher is installed for all users. This is usually solved by re-running the program as Administrator.  
**答**：权限错误，一般是 3.5 以上版本 Python 为所有用户安装，以非管理员身份运行本程序导致的。通常，以管理员身份重新运行本程序即可解决。

**Q: Encountered the error "No matching distribution found" and the warning "InsecurePlatformWarning" at the same time, how to solve?**  
**问：遇到“No matching distribution found”的报错和“InsecurePlatformWarning”的警告同时出现，该如何解决？**

**A**: SSLContext is not supported by the ssl module in Python 3.1, 2.7.8 and older. Switching the index to "Aliyun (PYPI)" will solve the problem.  
**答**：Python 3.1、2.7.8 及更旧的版本中 ssl 模块不支持 SSLContext 。切换索引至“阿里云（PYPI）”即可解决。

**Q: Encountered the error "TypeError: wrap_socket() got an unexpected keyword argument 'ciphers'", how to solve?**  
**问：遇到“TypeError: wrap_socket() got an unexpected keyword argument 'ciphers'”的报错，该如何解决？**

**A**: Python 3.1 is up to pip 6.0.3, which does not support the HTTPS protocol. Switching the index to "[HTTP] Aliyun (PYPI)" will solve the problem.  
**答**：Python 3.1 最高兼容 pip 6.0.3 ，这一版本的 pip 不支持 HTTPS 协议。切换索引至“[HTTP]阿里云（PYPI）”即可解决。

Donations  捐赠
=========

If you would like to support development, consider making a donation.  
如果您想支持开发，请考虑捐款。
- USDT address: TLZWKpYaH3XK5KYBVWVKQkXbSHUt2XnWJr
- Alipay 支付宝 / WeChat Pay 微信支付
![Scan the QR codes and donate](/donation.png)