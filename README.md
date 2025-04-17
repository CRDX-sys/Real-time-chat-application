# Real-Time Chat Application

[![Node.js](https://img.shields.io/badge/Node.js-16.x-green)]()
[![React](https://img.shields.io/badge/React-18.x-blue)]()
[![WebSocket](https://img.shields.io/badge/WebSocket-Enabled-brightgreen)]()

基于WebSocket的实时聊天应用，功能包括：
- 多房间聊天
- 用户在线状态
- 消息历史记录
- 文件共享

## 技术栈

**后端**:
- Node.js + Express
- Socket.IO
- MongoDB
- Redis (缓存)

**前端**:
- React 18
- Redux Toolkit
- Tailwind CSS
- Axios

## 快速开始

### 开发模式

1. 启动后端服务
```bash
cd server && npm install && npm run dev
```

2. 启动前端应用
```bash
cd client && npm install && npm start
```

### 生产构建

```bash
docker-compose up --build
```

## 环境变量

复制`.env.example`为`.env`并填写你的配置：
```
MONGODB_URI=mongodb://localhost:27017/chat
REDIS_URL=redis://localhost:6379
JWT_SECRET=your_secret_key
```

## 功能截图

![聊天界面](/docs/screenshots/chat.png)

## 贡献

欢迎提交Issue和PR。在提交代码前请运行：
```bash
npm test
```

## 许可证

MIT Licensed
