# Stock Dashboard WebSocket Server

## Render 배포 설정

### 필수 설정값
- **Build Command**: `npm ci`
- **Start Command**: `npm start`
- **Environment Variables**:
  - `NODE_ENV=production`
  - `PORT=10000`

### 배포 방법
1. Render에서 New Web Service 생성
2. GitHub 저장소 연결: `macaokim98/stock-dashboard-websocket`
3. 위 설정값 입력
4. Create Web Service 클릭

**중요**: Build Command는 반드시 `npm ci`로 설정해야 합니다.