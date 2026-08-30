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
── gitignore/               # Odoo 配置文件（已忽略）
── addons/               # 自定义插件目录
── README.md

# Local_erp_odoo

## 技术亮点
- 🐳 使用 Docker Compose 实现一键部署
- 🔧 支持自定义插件开发（./addons 目录）
- 📦 数据持久化配置
- 🔒 敏感信息通过环境变量管理

## 学习成果
- ERP 系统的采购业务流程（询价单 → 采购订单 → 收货 → 入库）
- Docker 容器化部署实践
- 供应链管理系统的基本架构
