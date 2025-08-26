# SCi - 校园信息助手

一个基于 Qt 开发的校园课程表、公告、地图查询系统。

## 功能特性

- 📅 课程表查询
- 📢 公告查看
- 🗺️ 校园地图（可缩放拖拽）
- 🔍 空教室查询
- ⚙️ 设置页面

## 技术栈

- Qt 6
- C++17
- CMake
- SQLite（本地缓存）
- MySQL（云端数据库）

## 构建说明

### 依赖

- Qt 6.x
- CMake 3.16+

### 构建命令

```bash
mkdir build && cd build
cmake ..
make -j4