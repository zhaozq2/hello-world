# 静态服务器信息

贪吃蛇游戏的静态HTTP服务器已启动！

## 访问方式

### 本地访问：
- **游戏页面**: http://localhost:8080/snake-game.html
- **目录列表**: http://localhost:8080/

### 网络访问（如果网络允许）：
- **游戏页面**: http://172.26.174.67:8080/snake-game.html
- **目录列表**: http://172.26.174.67:8080/

## 文件列表

1. **snake-game.html** - 贪吃蛇游戏主文件
2. **README.md** - 项目说明
3. **SNAKE_GAME_README.md** - 游戏详细文档
4. **.git/** - Git版本控制目录

## 游戏玩法

1. 打开游戏页面
2. 点击 "Start Game" 按钮
3. 使用 **箭头键** 或 **WASD** 控制蛇的移动
4. 吃红色食物得分（每个10分）
5. 避免撞墙或撞到自己
6. 游戏速度会随着得分增加而加快

## 服务器信息

- **端口**: 8080
- **协议**: HTTP
- **服务器**: Python HTTP Server
- **目录**: `/root/.openclaw/workspace/hello-world/`

## 停止服务器

要停止服务器，可以：
1. 在终端中按 `Ctrl+C`
2. 或者使用命令 `pkill -f "python3.*http.server"`

## 注意事项

- 确保端口8080没有被其他程序占用
- 如果无法访问，请检查防火墙设置
- 游戏需要现代浏览器支持HTML5 Canvas