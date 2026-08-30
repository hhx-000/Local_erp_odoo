#本地部署 Odoo ERP 采购系统

这是一个用于学习和演示的本地 Odoo ERP 系统，专注于采购和库存管理模块。

##技术栈
- Odoo 17.0 Community Edition
- PostgreSQL 15
- Docker & Docker Compose

##快速启动

```bash
docker-compose up -d

## 项目结构

── docker-compose.yml    # Docker 编排配置
── config/               # Odoo 配置文件（已忽略）
── addons/               # 自定义插件目录
── README.md

# Local_erp_odoo
