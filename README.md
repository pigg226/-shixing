# 服装扫码入库系统 — Docker 部署

## 项目结构
clothing-system/
├── index.html          # 前端代码（从 V3.1.txt 复制过来）
├── Dockerfile          # Docker 构建文件
└── docker-compose.yml  # Docker 编排配置

## 首次使用步骤

### 1. 把代码文件放进来
将桌面上的 V3.1.txt 重命名为 index.html，放到本文件夹中

### 2. 构建并启动
docker compose up -d

### 3. 打开浏览器访问
http://localhost:8080

### 4. 后期更新代码
用新的 index.html 替换旧文件，然后：
docker compose restart

### 5. 停止容器
docker compose down

### 6. 查看运行状态
docker compose ps
