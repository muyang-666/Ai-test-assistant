# AI Test Assistant

一个面向测试开发场景的 AI 自动化测试平台，支持：
- 测试用例管理
- LLM 生成 pytest 测试代码
- pytest 动态执行
- 日志分析
- 测试报告生成

## 技术栈
- Python
- FastAPI
- SQLAlchemy
- SQLite
- pytest
- httpx
- React
- Ant Design

## 项目结构
- backend: 后端服务
- frontend: 前端页面

## 启动方式
### 后端
uvicorn app.main:app --reload --port 8001

### 前端
npm run dev

## 功能说明
- 单接口测试闭环
- AI 代码生成
- 测试执行与结果回传
- 日志分析与报告生成
