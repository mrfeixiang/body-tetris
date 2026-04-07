# 🏋️ Body Tetris

Play Tetris with your body! Pose-controlled Tetris using [MediaPipe Pose](https://github.com/google/mediapipe) directly in your browser — no install required.

**🎮 Live Demo:** [GitHub Pages](https://mrfeixiang.github.io/body-tetris/) • [Vercel](https://body-tetris.vercel.app/)

[English](#english) • [한국어](#한국어) • [中文](#中文)

---

## English

### Overview
Body Tetris is a single-file HTML game that turns your webcam feed into a Tetris controller. Raise your arms to move, rotate, and slam pieces into place. Great for a quick workout while you play.

### Features
- 🎯 Real-time pose detection via MediaPipe
- 👻 Ghost piece preview
- 🔄 Wall-kick rotation
- ⏸ Pause / restart / game-over flow
- ⌨️ Keyboard fallback
- 📺 Mirrored webcam for intuitive control

### Controls
**Body**
- Raise **left arm** → move piece left
- Raise **right arm** → move piece right
- Raise **both arms** → rotate
- Lower **both arms** → hard drop

**Keyboard**
- `← → ↓` move • `↑` rotate • `Space` hard drop • `P` pause

### Run
Just open `index.html` in a modern browser (Chrome/Edge recommended) and grant camera permission. No build step needed.

```bash
git clone https://github.com/mrfeixiang/body-tetris.git
cd body-tetris
open index.html
```

---

## 한국어

### 소개
Body Tetris는 웹캠으로 몸을 움직여서 플레이하는 테트리스 게임입니다. MediaPipe Pose를 사용해 브라우저에서 바로 실행되며 설치가 필요 없습니다. 게임하면서 가벼운 운동도 할 수 있어요!

### 주요 기능
- 🎯 MediaPipe 기반 실시간 자세 인식
- 👻 고스트 블록 미리보기
- 🔄 벽 차기(wall-kick) 회전
- ⏸ 일시정지 / 재시작 / 게임 오버
- ⌨️ 키보드 대체 조작
- 📺 좌우 반전된 웹캠으로 직관적 조작

### 조작 방법
**몸 동작**
- **왼팔** 들기 → 블록 왼쪽 이동
- **오른팔** 들기 → 블록 오른쪽 이동
- **양팔** 들기 → 회전
- **양팔** 내리기 → 하드 드롭

**키보드**
- `← → ↓` 이동 • `↑` 회전 • `Space` 하드 드롭 • `P` 일시정지

### 실행 방법
최신 브라우저(Chrome/Edge 권장)에서 `index.html`을 열고 카메라 권한을 허용하면 됩니다. 빌드 과정이 필요 없습니다.

```bash
git clone https://github.com/mrfeixiang/body-tetris.git
cd body-tetris
open index.html
```

---

## 中文

### 简介
Body Tetris 是一款用身体来玩的俄罗斯方块游戏。基于 MediaPipe Pose 实现，直接在浏览器中运行，无需安装。一边玩一边轻松运动！

### 功能特性
- 🎯 基于 MediaPipe 的实时姿态识别
- 👻 幽灵方块落点预览
- 🔄 靠墙旋转修正（wall-kick）
- ⏸ 暂停 / 重启 / 游戏结束流程
- ⌨️ 键盘备用操作
- 📺 镜像摄像头画面，操作更直观

### 操作方式
**身体动作**
- 抬起**左臂** → 方块向左移动
- 抬起**右臂** → 方块向右移动
- **双臂同时举起** → 旋转
- **双臂同时放下** → 直接落下

**键盘**
- `← → ↓` 移动 • `↑` 旋转 • `Space` 硬降 • `P` 暂停

### 运行方法
在现代浏览器（推荐 Chrome/Edge）中打开 `index.html` 并允许摄像头权限即可。无需任何构建步骤。

```bash
git clone https://github.com/mrfeixiang/body-tetris.git
cd body-tetris
open index.html
```

---

## License
MIT
