<p align="right">
  <a href="./README.md">English</a> | 简体中文
</p>

# esp32_ble_web

用 **Web Bluetooth** 在浏览器里连接 ESP32-CAM：  
- 获取图像数据

## 文件说明
- `esp32_cam_ble.ino` – 单片机代码
- `index.html` – 网页（默认入口）
- `esp32_cam_ble_web_no_css.html` – **无 CSS 极简版**，结构与逻辑基本一致

## 协议与 UUID
- **Service UUID**：`19b10000-e8f2-537e-4f6c-d104768a1214`

## 如何使用
1. **烧录固件**  
   - Arduino IDE 选择 ESP32 开发板 → 打开 `esp32_cam_ble.ino` → 烧录。  
2. **打开网页**  
   - 直接打开 `index.html`（或部署到 GitHub Pages，见下）。  
   - 浏览器：**Chrome/Edge/Android** 直接可用；**iOS** 请用 **Bluefy** App 打开。  
3. **连接与操作**  
   - 点击 **Connect** → 选择你的 ESP32。  

## GitHub Pages（可选）
1. 仓库 **Settings → Pages**  
2. **Source** 选 `Deploy from a branch`，分支 `main`，目录 `/root`，保存  
3. 等待部署完成，访问：  
   `https://tianqi-yao.github.io/esp32-cam_ble_web/`
