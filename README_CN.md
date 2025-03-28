# Odoo ERP系统

Odoo是一个开源的企业资源规划(ERP)系统，提供全面的业务管理解决方案。

## 项目结构说明

### 主要目录

- `addons/`: 核心模块目录，包含所有Odoo应用模块
- `odoo/`: Odoo框架核心代码
- `doc/`: 项目文档
- `setup/`: 安装和配置相关文件
- `debian/`: Debian/Ubuntu系统打包相关文件

### 重要文件

- `odoo-bin`: Odoo服务器启动脚本
- `requirements.txt`: Python依赖包列表
- `setup.py`: Python包安装配置文件
- `LICENSE`: LGPLv3许可证文件
- `SECURITY.md`: 安全策略文档
- `CONTRIBUTING.md`: 贡献指南

## 许可证分析

Odoo使用LGPLv3许可证，这意味着：

1. 商业使用许可：
   - 可以免费用于商业用途
   - 可以修改源代码
   - 可以分发修改后的版本

2. 主要限制：
   - 必须保持开源
   - 修改后的代码必须使用相同的许可证
   - 必须提供源代码访问方式

3. 商业部署要求：
   - 需要提供源代码访问方式
   - 需要包含许可证声明
   - 需要说明修改内容

## 商业使用建议

1. 合规性：
   - 确保遵守LGPLv3许可证要求
   - 保留所有版权声明
   - 提供源代码访问方式

2. 技术支持：
   - 建议购买Odoo企业版支持
   - 或寻找第三方技术支持服务

3. 定制开发：
   - 可以开发自定义模块
   - 建议遵循Odoo开发规范
   - 注意代码质量维护

## 安装说明

1. 系统要求：
   - Python 3.7+
   - PostgreSQL 9.6+
   - 其他依赖见requirements.txt

2. 安装步骤：
   ```bash
   # 安装依赖
   pip install -r requirements.txt
   
   # 启动服务
   ./odoo-bin -c odoo.conf
   ```

## 技术支持

- 官方文档：https://www.odoo.com/documentation/
- 社区论坛：https://www.odoo.com/forum/
- 企业支持：https://www.odoo.com/enterprise/ 