# MVP-atraxworld-
atrax-world/
│
├── README.md
├── .gitignore
├── package.json
├── .env.example
│
├── assets/                          # Thư mục assets do ZAH quản lý
│   ├── logo/
│   │   └── atrax-world-logo.png
│   │
│   ├── ui/
│   │   ├── panels/
│   │   │   ├── login-panel-zah.png
│   │   │   ├── register-panel-zah.png
│   │   │   ├── profile-edit-panel-zah.png
│   │   │   ├── stream-question-panel-zah.png
│   │   │   ├── donation-notification-panel-zah.png
│   │   │   ├── donation-send-panel-zah.png
│   │   │   └── inventory-panel-zah.png
│   │   │
│   │   ├── buttons/
│   │   │   ├── play-game-button-zah.png
│   │   │   ├── watch-stream-button-zah.png
│   │   │   ├── home-button-zah.png
│   │   │   ├── connect-wallet-button-zah.png
│   │   │   ├── donate-button-zah.png
│   │   │   └── copy-wallet-button-zah.png
│   │   │
│   │   └── icons/
│   │       ├── sol-icon-zah.png
│   │       ├── wallet-icon-zah.png
│   │       └── chat-icon-zah.png
│   │
│   ├── game/
│   │   ├── biomes/
│   │   │   ├── plains/
│   │   │   │   ├── ground-tile-plains-zah.png
│   │   │   │   └── background-plains-zah.png
│   │   │   ├── desert/
│   │   │   ├── island/
│   │   │   └── snow/
│   │   │
│   │   ├── buildings/
│   │   │   ├── house-level-1-zah.png
│   │   │   ├── house-level-2-zah.png
│   │   │   ├── house-level-3-zah.png
│   │   │   ├── house-level-4-zah.png
│   │   │   ├── farm-level-1-zah.png
│   │   │   ├── farm-level-2-zah.png
│   │   │   ├── farm-level-3-zah.png
│   │   │   ├── shop-level-1-zah.png
│   │   │   ├── windmill-level-1-zah.png
│   │   │   ├── pig-pen-level-1-zah.png
│   │   │   ├── pig-pen-level-2-zah.png
│   │   │   ├── pig-pen-level-3-zah.png
│   │   │   ├── horse-stable-level-1-zah.png
│   │   │   ├── horse-stable-level-2-zah.png
│   │   │   └── horse-stable-level-3-zah.png
│   │   │
│   │   ├── structures/
│   │   │   ├── wooden-fence-zah.png
│   │   │   ├── stone-fence-zah.png
│   │   │   ├── wooden-door-zah.png
│   │   │   ├── iron-door-zah.png
│   │   │   └── fence-level-1-zah.png
│   │   │
│   │   ├── crops/
│   │   │   ├── farmland-level-1-zah.png
│   │   │   ├── farmland-level-2-zah.png
│   │   │   ├── farmland-level-3-zah.png
│   │   │   ├── farmland-level-4-zah.png
│   │   │   ├── wheat-level-1-zah.png
│   │   │   ├── wheat-level-2-zah.png
│   │   │   ├── wheat-level-3-zah.png
│   │   │   ├── wheat-level-4-zah.png
│   │   │   ├── corn-plant-level-1-zah.png
│   │   │   ├── corn-plant-level-2-zah.png
│   │   │   ├── corn-plant-level-3-zah.png
│   │   │   ├── corn-plant-level-4-zah.png
│   │   │   └── corn-item-zah.png
│   │   │
│   │   └── units/
│   │       ├── melee-soldier-level-1-zah.png
│   │       ├── melee-soldier-level-2-zah.png
│   │       ├── melee-soldier-level-3-zah.png
│   │       ├── archer-level-1-zah.png
│   │       ├── archer-level-2-zah.png
│   │       ├── archer-level-3-zah.png
│   │       ├── cavalry-level-1-zah.png
│   │       ├── cavalry-level-2-zah.png
│   │       ├── cavalry-level-3-zah.png
│   │       ├── guard-level-1-zah.png
│   │       ├── guard-level-2-zah.png
│   │       └── guard-level-3-zah.png
│   │
│   └── avatars/
│       ├── default-avatar-1-zah.png
│       ├── default-avatar-2-zah.png
│       └── default-avatar-3-zah.png
│
├── public/
│   ├── index.html
│   └── favicon.ico
│
├── src/
│   ├── pages/                       # Pages do ZAH quản lý
│   │   ├── HomePage-zah.jsx
│   │   ├── GamePage-zah.jsx
│   │   └── ViewerPage-zah.jsx
│   │
│   ├── components/                  # Components chia theo người làm
│   │   ├── home/
│   │   │   ├── LoginModal-zah.jsx
│   │   │   ├── RegisterModal-zah.jsx
│   │   │   ├── HomeHeader-zah.jsx
│   │   │   └── NavigationButtons-zah.jsx
│   │   │
│   │   ├── game/
│   │   │   ├── GameCanvas-zah.jsx          # Canvas chính game
│   │   │   ├── ProfileEditModal-zah.jsx
│   │   │   ├── StreamQuestionModal-zah.jsx
│   │   │   ├── DonationNotification-zah.jsx
│   │   │   ├── ChatBox-zah.jsx
│   │   │   ├── PlayerInfo-zah.jsx
│   │   │   ├── WalletDisplay-zah.jsx
│   │   │   ├── BuildValueDisplay-zah.jsx
│   │   │   ├── InventoryPanel-zah.jsx
│   │   │   ├── OrientationWarning-zah.jsx
│   │   │   └── GameController-zah.js       # Logic điều khiển game
│   │   │
│   │   ├── viewer/                          # Viewer components - DUY quản lý
│   │   │   ├── StreamList-duy.jsx
│   │   │   ├── VideoPlayer-duy.jsx
│   │   │   ├── DonateButton-duy.jsx
│   │   │   ├── DonateModal-duy.jsx
│   │   │   ├── DonationHistory-duy.jsx
│   │   │   ├── ViewerWalletDisplay-duy.jsx
│   │   │   ├── ViewerInfo-duy.jsx
│   │   │   └── ChatBoxViewer-duy.jsx
│   │   │
│   │   └── shared/                  # Components dùng chung
│   │       ├── WalletConnectButton-zah.jsx
│   │       ├── HomeButton-zah.jsx
│   │       └── LoadingSpinner-zah.jsx
│   │
│   ├── game-engine/                 # Game engine - ZAH quản lý
│   │   ├── core/
│   │   │   ├── GameManager-zah.js
│   │   │   ├── WorldManager-zah.js
│   │   │   ├── MapGenerator-zah.js
│   │   │   └── CameraController-zah.js
│   │   │
│   │   ├── entities/
│   │   │   ├── Player-zah.js
│   │   │   ├── Building-zah.js
│   │   │   ├── Unit-zah.js
│   │   │   ├── Crop-zah.js
│   │   │   └── Structure-zah.js
│   │   │
│   │   ├── systems/
│   │   │   ├── BuildingSystem-zah.js
│   │   │   ├── InventorySystem-zah.js
│   │   │   ├── PlacementSystem-zah.js
│   │   │   └── RenderSystem-zah.js
│   │   │
│   │   └── data/
│   │       ├── items-data-zah.json
│   │       ├── buildings-data-zah.json
│   │       └── biomes-data-zah.json
│   │
│   ├── blockchain/                  # Blockchain logic - DUY quản lý
│   │   ├── wallet/
│   │   │   ├── WalletAdapter-duy.js
│   │   │   ├── WalletProvider-duy.jsx
│   │   │   └── WalletUtils-duy.js
│   │   │
│   │   ├── transactions/
│   │   │   ├── DonateTransaction-duy.js
│   │   │   ├── BuyItemTransaction-duy.js
│   │   │   └── ClaimProfitTransaction-duy.js
│   │   │
│   │   ├── contracts/
│   │   │   └── AtraxContract-duy.js
│   │   │
│   │   └── utils/
│   │       ├── solana-utils-duy.js
│   │       └── transaction-builder-duy.js
│   │
│   ├── api/                         # API integration
│   │   ├── youtube/
│   │   │   ├── YouTubeAPI-zah.js           # YouTube embed
│   │   │   └── StreamValidator-zah.js
│   │   │
│   │   ├── backend/
│   │   │   ├── auth-api-zah.js
│   │   │   ├── game-api-zah.js
│   │   │   ├── stream-api-duy.js           # Stream list API
│   │   │   └── donation-api-duy.js         # Donation tracking
│   │   │
│   │   └── websocket/
│   │       ├── GameWebSocket-zah.js
│   │       ├── ChatWebSocket-zah.js
│   │       └── DonationWebSocket-duy.js
│   │
│   ├── hooks/                       # Custom hooks
│   │   ├── useAuth-zah.js
│   │   ├── useGame-zah.js
│   │   ├── useWallet-duy.js
│   │   ├── useDonation-duy.js
│   │   └── useStream-duy.js
│   │
│   ├── context/                     # Context providers
│   │   ├── AuthContext-zah.jsx
│   │   ├── GameContext-zah.jsx
│   │   ├── WalletContext-duy.jsx
│   │   └── StreamContext-duy.jsx
│   │
│   ├── utils/                       # Utilities
│   │   ├── constants-zah.js
│   │   ├── helpers-zah.js
│   │   └── validators-duy.js
│   │
│   ├── styles/                      # Styles
│   │   ├── global-zah.css
│   │   ├── game-zah.css
│   │   └── viewer-duy.css
│   │
│   ├── App.jsx                      # Main app - ZAH
│   └── index.js                     # Entry point
│
├── backend/                         # Backend server (nếu cần)
│   ├── src/
│   │   ├── controllers/
│   │   │   ├── auth-controller-zah.js
│   │   │   ├── game-controller-zah.js
│   │   │   ├── stream-controller-duy.js
│   │   │   └── donation-controller-duy.js
│   │   │
│   │   ├── models/
│   │   │   ├── User-zah.js
│   │   │   ├── GameState-zah.js
│   │   │   ├── Stream-duy.js
│   │   │   └── Donation-duy.js
│   │   │
│   │   ├── routes/
│   │   │   ├── auth-routes-zah.js
│   │   │   ├── game-routes-zah.js
│   │   │   ├── stream-routes-duy.js
│   │   │   └── donation-routes-duy.js
│   │   │
│   │   ├── services/
│   │   │   ├── database-service-zah.js
│   │   │   ├── youtube-service-zah.js
│   │   │   └── blockchain-service-duy.js
│   │   │
│   │   ├── middleware/
│   │   │   ├── auth-middleware-zah.js
│   │   │   └── validation-middleware-zah.js
│   │   │
│   │   └── server.js
│   │
│   ├── package.json
│   └── .env.example
│
├── solana-program/                  # Anchor Program - DUY quản lý
│   ├── programs/
│   │   └── atrax/
│   │       ├── src/
│   │       │   ├── lib-duy.rs              # Main program
│   │       │   ├── instructions/
│   │       │   │   ├── donate-duy.rs
│   │       │   │   ├── buy_item-duy.rs
│   │       │   │   └── claim_profit-duy.rs
│   │       │   ├── state/
│   │       │   │   ├── donation-duy.rs
│   │       │   │   ├── item-duy.rs
│   │       │   │   └── profit-duy.rs
│   │       │   └── errors-duy.rs
│   │       │
│   │       └── Cargo.toml
│   │
│   ├── tests/
│   │   └── atrax-test-duy.ts
│   │
│   ├── migrations/
│   │   └── deploy-duy.ts
│   │
│   ├── Anchor.toml
│   └── package.json
│
├── docs/                            # Documentation
│   ├── ARCHITECTURE.md
│   ├── API.md
│   ├── BLOCKCHAIN.md               # DUY viết
│   ├── GAME_MECHANICS.md           # ZAH viết
│   └── DEPLOYMENT.md
│
└── scripts/                        # Build & deployment scripts
    ├── build-zah.sh
    ├── deploy-frontend-zah.sh
    └── deploy-program-duy.sh


### Hướng dẫn chi tiết từng file 
ZAH - Game & Frontend Core:

✅ Home Page (login, register, navigation)
✅ Game Page (toàn bộ game engine, canvas, building system)
✅ Game Components (inventory, player info, chat)
✅ YouTube integration
✅ Backend API cho auth và game state
✅ Toàn bộ asset game và UI panels

DUY - Blockchain & Viewer:

✅ Viewer Page (stream list, video player)
✅ Viewer Components (donate modal, donation history)
✅ Wallet integration (Phantom, Solflare, Glow, MetaMask)
✅ Smart contract (Anchor program)
✅ Blockchain transactions (donate, buy item, claim profit)
✅ Donation tracking system

---

## 📋 HƯỚNG DẪN CHI TIẾT TỪNG FILE

### 🏠 **ROOT FILES**

#### `README.md`
- Viết mô tả tổng quan về dự án Atrax World
- Hướng dẫn cài đặt và chạy dự án
- Liệt kê các tính năng chính
- Hướng dẫn build và deploy
- Thông tin về team và phân chia trách nhiệm

#### `.gitignore`
- Thêm các pattern ignore cho Node.js, React, Solana
- Ignore file .env, node_modules, dist, build
- Ignore file log, cache, temp
- Ignore file IDE (vscode, webstorm)

#### `package.json`
- Định nghĩa dependencies cho React frontend
- Scripts: start, build, test, deploy
- Metadata: name, version, description
- Dependencies: React, React Router, Canvas API, WebSocket

#### `.env.example`
- Template cho các biến môi trường
- API keys, database URLs, blockchain endpoints
- YouTube API key, Solana RPC URLs
- Backend server URLs

---

### 🎨 **ASSETS FOLDER**

#### `assets/logo/atrax-world-logo.png`
- Thiết kế logo chính của game
- Kích thước: 512x512px, format PNG
- Style: pixel art, màu sắc tươi sáng
- Có thể tạo nhiều phiên bản (light/dark mode)

#### `assets/ui/panels/` (Tất cả file .png)
- **login-panel-zah.png**: Background cho modal đăng nhập
- **register-panel-zah.png**: Background cho modal đăng ký
- **profile-edit-panel-zah.png**: Panel chỉnh sửa profile
- **stream-question-panel-zah.png**: Panel đặt câu hỏi cho streamer
- **donation-notification-panel-zah.png**: Thông báo donation
- **donation-send-panel-zah.png**: Panel gửi donation
- **inventory-panel-zah.png**: Panel inventory game
- Kích thước: 800x600px, style pixel art, có border và shadow

#### `assets/ui/buttons/` (Tất cả file .png)
- **play-game-button-zah.png**: Nút bắt đầu chơi game
- **watch-stream-button-zah.png**: Nút xem stream
- **home-button-zah.png**: Nút về trang chủ
- **connect-wallet-button-zah.png**: Nút kết nối ví
- **donate-button-zah.png**: Nút donate
- **copy-wallet-button-zah.png**: Nút copy địa chỉ ví
- Kích thước: 200x60px, có hover states, style pixel art

#### `assets/ui/icons/` (Tất cả file .png)
- **sol-icon-zah.png**: Icon SOL token
- **wallet-icon-zah.png**: Icon ví tiền
- **chat-icon-zah.png**: Icon chat
- Kích thước: 32x32px, style pixel art, transparent background

#### `assets/game/biomes/` (Tất cả file .png)
- **plains/**: Tile và background cho biome đồng bằng
- **desert/**: Tile và background cho biome sa mạc
- **island/**: Tile và background cho biome đảo
- **snow/**: Tile và background cho biome tuyết
- Kích thước tile: 64x64px, background: 1920x1080px

#### `assets/game/buildings/` (Tất cả file .png)
- Các level của nhà: house-level-1 đến 4
- Các level của farm: farm-level-1 đến 3
- Các building khác: shop, windmill, pig-pen, horse-stable
- Kích thước: 128x128px, style pixel art, có animation frames

#### `assets/game/structures/` (Tất cả file .png)
- Fence, door, các cấu trúc phụ
- Kích thước: 64x64px, có thể tiling

#### `assets/game/crops/` (Tất cả file .png)
- Farmland và các loại cây trồng
- Các giai đoạn phát triển của cây
- Kích thước: 64x64px, có animation growth

#### `assets/game/units/` (Tất cả file .png)
- Các loại đơn vị quân: melee, archer, cavalry, guard
- Các level khác nhau của từng loại
- Kích thước: 64x64px, có animation idle/walk/attack

#### `assets/avatars/` (Tất cả file .png)
- Avatar mặc định cho player
- Kích thước: 128x128px, style pixel art

---

### 🌐 **PUBLIC FOLDER**

#### `public/index.html`
- HTML template chính cho React app
- Meta tags, title, favicon
- Root div cho React mounting
- Import các font và CSS cơ bản

#### `public/favicon.ico`
- Icon hiển thị trên browser tab
- Kích thước: 32x32px, format ICO

---

### 📱 **SRC FOLDER - PAGES**

#### `src/pages/HomePage-zah.jsx`
- Trang chủ với navigation buttons
- Hiển thị logo và mô tả game
- Nút Play Game và Watch Stream
- Modal login/register integration

#### `src/pages/GamePage-zah.jsx`
- Trang chính chứa game canvas
- Layout với game area và UI panels
- Integration với game engine
- Responsive design cho mobile

#### `src/pages/ViewerPage-zah.jsx`
- Trang xem stream với video player
- Stream list và chat integration
- Donation system integration
- Layout cho viewer experience

---

### 🧩 **SRC FOLDER - COMPONENTS**

#### `src/components/home/LoginModal-zah.jsx`
- Modal đăng nhập với form validation
- Integration với auth API
- Error handling và loading states
- Responsive design

#### `src/components/home/RegisterModal-zah.jsx`
- Modal đăng ký tài khoản
- Form validation cho username, email, password
- Integration với auth API
- Terms of service checkbox

#### `src/components/home/HomeHeader-zah.jsx`
- Header component cho trang chủ
- Logo và navigation menu
- User status display
- Responsive navigation

#### `src/components/home/NavigationButtons-zah.jsx`
- Các nút navigation chính
- Play Game, Watch Stream, Home buttons
- Hover effects và animations
- Integration với routing

#### `src/components/game/GameCanvas-zah.jsx`
- Canvas element chính cho game
- Integration với game engine
- Event handlers cho mouse/touch
- Responsive canvas sizing

#### `src/components/game/ProfileEditModal-zah.jsx`
- Modal chỉnh sửa profile player
- Avatar selection, username change
- Statistics display
- Save/cancel functionality

#### `src/components/game/StreamQuestionModal-zah.jsx`
- Modal đặt câu hỏi cho streamer
- Text input với character limit
- Submit question functionality
- Integration với chat system

#### `src/components/game/DonationNotification-zah.jsx`
- Component hiển thị thông báo donation
- Animation effects cho notification
- Auto-hide after timeout
- Sound effects integration

#### `src/components/game/ChatBox-zah.jsx`
- Chat interface cho game
- Message history và input
- Emoji support
- Integration với WebSocket

#### `src/components/game/PlayerInfo-zah.jsx`
- Hiển thị thông tin player
- Level, experience, resources
- Avatar và username
- Real-time updates

#### `src/components/game/WalletDisplay-zah.jsx`
- Hiển thị thông tin ví
- SOL balance và transaction history
- Connect/disconnect wallet
- Copy address functionality

#### `src/components/game/BuildValueDisplay-zah.jsx`
- Hiển thị giá trị xây dựng
- Cost calculation cho buildings
- Resource requirements
- Real-time updates

#### `src/components/game/InventoryPanel-zah.jsx`
- Panel hiển thị inventory
- Item grid với drag & drop
- Item details và tooltips
- Use/sell item functionality

#### `src/components/game/OrientationWarning-zah.jsx`
- Warning cho mobile orientation
- Detect landscape/portrait mode
- Show warning message
- Auto-hide functionality

#### `src/components/game/GameController-zah.js`
- Logic điều khiển game chính
- Keyboard/mouse event handling
- Game state management
- Integration với game engine

#### `src/components/viewer/StreamList-duy.jsx`
- Danh sách các stream đang live
- Filter và search functionality
- Streamer info và viewer count
- Click to join stream

#### `src/components/viewer/VideoPlayer-duy.jsx`
- YouTube video player integration
- Fullscreen support
- Quality selection
- Playback controls

#### `src/components/viewer/DonateButton-duy.jsx`
- Nút donate cho streamer
- Amount selection
- Wallet integration
- Transaction confirmation

#### `src/components/viewer/DonateModal-duy.jsx`
- Modal gửi donation
- Amount input và message
- Wallet connection check
- Transaction processing

#### `src/components/viewer/DonationHistory-duy.jsx`
- Lịch sử donations đã gửi
- Filter theo streamer/date
- Transaction details
- Export functionality

#### `src/components/viewer/ViewerWalletDisplay-duy.jsx`
- Hiển thị ví cho viewer
- SOL balance
- Recent transactions
- Connect wallet button

#### `src/components/viewer/ViewerInfo-duy.jsx`
- Thông tin viewer
- Username và avatar
- Donation statistics
- Achievement badges

#### `src/components/viewer/ChatBoxViewer-duy.jsx`
- Chat cho viewer
- Message history
- Emoji và reactions
- Moderation tools

#### `src/components/shared/WalletConnectButton-zah.jsx`
- Button kết nối ví chung
- Support multiple wallets
- Connection status
- Error handling

#### `src/components/shared/HomeButton-zah.jsx`
- Button về trang chủ
- Navigation functionality
- Icon và styling
- Responsive design

#### `src/components/shared/LoadingSpinner-zah.jsx`
- Loading spinner component
- Multiple sizes và colors
- Animation effects
- Reusable across app

---

### 🎮 **SRC FOLDER - GAME ENGINE**

#### `src/game-engine/core/GameManager-zah.js`
- Quản lý game state chính
- Game loop và update cycle
- Event system
- Integration với các systems

#### `src/game-engine/core/WorldManager-zah.js`
- Quản lý world map
- Chunk loading/unloading
- Biome generation
- World persistence

#### `src/game-engine/core/MapGenerator-zah.js`
- Tạo map procedural
- Biome placement
- Resource distribution
- Map optimization

#### `src/game-engine/core/CameraController-zah.js`
- Camera movement và zoom
- Smooth transitions
- Boundary limits
- Touch/mouse controls

#### `src/game-engine/entities/Player-zah.js`
- Player entity class
- Movement và actions
- Stats và inventory
- Network synchronization

#### `src/game-engine/entities/Building-zah.js`
- Building entity class
- Construction logic
- Upgrade system
- Resource production

#### `src/game-engine/entities/Unit-zah.js`
- Unit entity class
- AI behavior
- Combat system
- Pathfinding

#### `src/game-engine/entities/Crop-zah.js`
- Crop entity class
- Growth cycle
- Harvest mechanics
- Weather effects

#### `src/game-engine/entities/Structure-zah.js`
- Structure entity class
- Placement rules
- Decorative elements
- Collision detection

#### `src/game-engine/systems/BuildingSystem-zah.js`
- Building placement logic
- Construction validation
- Upgrade requirements
- Resource management

#### `src/game-engine/systems/InventorySystem-zah.js`
- Inventory management
- Item stacking
- Drag & drop
- Item usage

#### `src/game-engine/systems/PlacementSystem-zah.js`
- Object placement logic
- Collision detection
- Grid snapping
- Preview system

#### `src/game-engine/systems/RenderSystem-zah.js`
- Rendering pipeline
- Sprite management
- Animation system
- Performance optimization

#### `src/game-engine/data/items-data-zah.json`
- Database các items trong game
- Properties: name, type, value, rarity
- Crafting recipes
- Item descriptions

#### `src/game-engine/data/buildings-data-zah.json`
- Database các buildings
- Properties: cost, production, upgrade
- Placement rules
- Visual assets

#### `src/game-engine/data/biomes-data-zah.json`
- Database các biomes
- Properties: resources, weather, difficulty
- Visual themes
- Spawn rates

---

### ⛓️ **SRC FOLDER - BLOCKCHAIN**

#### `src/blockchain/wallet/WalletAdapter-duy.js`
- Wallet adapter interface
- Support Phantom, Solflare, Glow
- Connection management
- Error handling

#### `src/blockchain/wallet/WalletProvider-duy.jsx`
- React context cho wallet
- Global wallet state
- Connection status
- Provider setup

#### `src/blockchain/wallet/WalletUtils-duy.js`
- Utility functions cho wallet
- Address validation
- Balance checking
- Transaction helpers

#### `src/blockchain/transactions/DonateTransaction-duy.js`
- Donation transaction logic
- Amount validation
- Fee calculation
- Transaction signing

#### `src/blockchain/transactions/BuyItemTransaction-duy.js`
- Item purchase transaction
- Price validation
- Inventory update
- Receipt generation

#### `src/blockchain/transactions/ClaimProfitTransaction-duy.js`
- Profit claiming logic
- Balance calculation
- Tax handling
- Payout processing

#### `src/blockchain/contracts/AtraxContract-duy.js`
- Smart contract interface
- Method definitions
- Event handling
- Error management

#### `src/blockchain/utils/solana-utils-duy.js`
- Solana utility functions
- RPC calls
- Transaction building
- Account management

#### `src/blockchain/utils/transaction-builder-duy.js`
- Transaction builder utility
- Instruction creation
- Fee estimation
- Batch transactions

---

### 🔌 **SRC FOLDER - API**

#### `src/api/youtube/YouTubeAPI-zah.js`
- YouTube API integration
- Video embedding
- Stream validation
- API key management

#### `src/api/youtube/StreamValidator-zah.js`
- Stream validation logic
- Live status checking
- Stream quality validation
- Error handling

#### `src/api/backend/auth-api-zah.js`
- Authentication API calls
- Login/logout/register
- Token management
- User profile

#### `src/api/backend/game-api-zah.js`
- Game state API
- Save/load game
- Leaderboards
- Statistics

#### `src/api/backend/stream-api-duy.js`
- Stream management API
- Stream list
- Streamer info
- Live status

#### `src/api/backend/donation-api-duy.js`
- Donation tracking API
- Transaction history
- Statistics
- Analytics

#### `src/api/websocket/GameWebSocket-zah.js`
- Game WebSocket connection
- Real-time updates
- Multiplayer sync
- Error handling

#### `src/api/websocket/ChatWebSocket-zah.js`
- Chat WebSocket
- Message broadcasting
- User management
- Moderation

#### `src/api/websocket/DonationWebSocket-duy.js`
- Donation WebSocket
- Real-time notifications
- Transaction updates
- Live tracking

---

### 🎣 **SRC FOLDER - HOOKS**

#### `src/hooks/useAuth-zah.js`
- Authentication hook
- User state management
- Login/logout functions
- Token handling

#### `src/hooks/useGame-zah.js`
- Game state hook
- Game data management
- Save/load functions
- Progress tracking

#### `src/hooks/useWallet-duy.js`
- Wallet connection hook
- Balance tracking
- Transaction status
- Connection management

#### `src/hooks/useDonation-duy.js`
- Donation hook
- Transaction handling
- History management
- Statistics

#### `src/hooks/useStream-duy.js`
- Stream data hook
- Live status tracking
- Streamer info
- Viewer count

---

### 🎯 **SRC FOLDER - CONTEXT**

#### `src/context/AuthContext-zah.jsx`
- Authentication context provider
- Global auth state
- User session management
- Protected routes

#### `src/context/GameContext-zah.jsx`
- Game context provider
- Game state management
- Player data
- Game settings

#### `src/context/WalletContext-duy.jsx`
- Wallet context provider
- Wallet connection state
- Balance tracking
- Transaction history

#### `src/context/StreamContext-duy.jsx`
- Stream context provider
- Stream data management
- Live status
- Streamer information

---

### 🛠️ **SRC FOLDER - UTILS**

#### `src/utils/constants-zah.js`
- Game constants
- Configuration values
- Asset paths
- API endpoints

#### `src/utils/helpers-zah.js`
- Utility functions
- Format helpers
- Validation functions
- Common calculations

#### `src/utils/validators-duy.js`
- Validation functions
- Input validation
- Transaction validation
- Error checking

---

### 🎨 **SRC FOLDER - STYLES**

#### `src/styles/global-zah.css`
- Global CSS styles
- CSS variables
- Reset styles
- Common classes

#### `src/styles/game-zah.css`
- Game-specific styles
- Canvas styling
- UI component styles
- Animation keyframes

#### `src/styles/viewer-duy.css`
- Viewer page styles
- Video player styling
- Chat interface
- Donation UI

---

### 📱 **SRC FOLDER - MAIN FILES**

#### `src/App.jsx`
- Main React component
- Router setup
- Context providers
- Global error handling

#### `src/index.js`
- React app entry point
- DOM mounting
- Service worker registration
- Error boundaries

---

### 🖥️ **BACKEND FOLDER**

#### `backend/src/controllers/auth-controller-zah.js`
- Authentication controller
- Login/logout endpoints
- User registration
- Token validation

#### `backend/src/controllers/game-controller-zah.js`
- Game state controller
- Save/load endpoints
- Leaderboards
- Statistics

#### `backend/src/controllers/stream-controller-duy.js`
- Stream management controller
- Stream CRUD operations
- Live status updates
- Streamer management

#### `backend/src/controllers/donation-controller-duy.js`
- Donation controller
- Transaction processing
- History tracking
- Analytics

#### `backend/src/models/User-zah.js`
- User data model
- Schema definition
- Validation rules
- Database operations

#### `backend/src/models/GameState-zah.js`
- Game state model
- Player progress
- World data
- Save system

#### `backend/src/models/Stream-duy.js`
- Stream data model
- Streamer info
- Live status
- Metadata

#### `backend/src/models/Donation-duy.js`
- Donation model
- Transaction data
- Amount tracking
- Timestamps

#### `backend/src/routes/auth-routes-zah.js`
- Authentication routes
- Endpoint definitions
- Middleware setup
- Error handling

#### `backend/src/routes/game-routes-zah.js`
- Game routes
- API endpoints
- Request validation
- Response formatting

#### `backend/src/routes/stream-routes-duy.js`
- Stream routes
- CRUD operations
- Search/filter
- Pagination

#### `backend/src/routes/donation-routes-duy.js`
- Donation routes
- Transaction endpoints
- History queries
- Statistics

#### `backend/src/services/database-service-zah.js`
- Database connection
- Query helpers
- Transaction management
- Connection pooling

#### `backend/src/services/youtube-service-zah.js`
- YouTube API service
- Stream validation
- Video metadata
- API rate limiting

#### `backend/src/services/blockchain-service-duy.js`
- Blockchain integration
- Transaction monitoring
- Event processing
- Error handling

#### `backend/src/middleware/auth-middleware-zah.js`
- Authentication middleware
- Token validation
- User authorization
- Protected routes

#### `backend/src/middleware/validation-middleware-zah.js`
- Input validation
- Schema validation
- Error formatting
- Request sanitization

#### `backend/src/server.js`
- Express server setup
- Middleware configuration
- Route registration
- Error handling

#### `backend/package.json`
- Backend dependencies
- Scripts configuration
- Metadata
- Environment setup

#### `backend/.env.example`
- Backend environment variables
- Database configuration
- API keys
- Server settings

---

### ⛓️ **SOLANA PROGRAM FOLDER**

#### `solana-program/programs/atrax/src/lib-duy.rs`
- Main Anchor program
- Program entry point
- Instruction handlers
- Error definitions

#### `solana-program/programs/atrax/src/instructions/donate-duy.rs`
- Donation instruction
- Amount validation
- Account management
- Event emission

#### `solana-program/programs/atrax/src/instructions/buy_item-duy.rs`
- Item purchase instruction
- Price validation
- Inventory updates
- Receipt generation

#### `solana-program/programs/atrax/src/instructions/claim_profit-duy.rs`
- Profit claiming instruction
- Balance calculation
- Tax handling
- Payout processing

#### `solana-program/programs/atrax/src/state/donation-duy.rs`
- Donation state struct
- Data validation
- Serialization
- Account constraints

#### `solana-program/programs/atrax/src/state/item-duy.rs`
- Item state struct
- Properties definition
- Validation rules
- Metadata

#### `solana-program/programs/atrax/src/state/profit-duy.rs`
- Profit state struct
- Balance tracking
- Calculation logic
- Payout rules

#### `solana-program/programs/atrax/src/errors-duy.rs`
- Custom error definitions
- Error codes
- Error messages
- Validation errors

#### `solana-program/programs/atrax/Cargo.toml`
- Rust dependencies
- Anchor framework
- Solana programs
- Build configuration

#### `solana-program/tests/atrax-test-duy.ts`
- Program tests
- Instruction testing
- Integration tests
- Error testing

#### `solana-program/migrations/deploy-duy.ts`
- Deployment script
- Program deployment
- Account initialization
- Configuration

#### `solana-program/Anchor.toml`
- Anchor configuration
- Program settings
- Network configuration
- Build settings

#### `solana-program/package.json`
- Node.js dependencies
- Anchor CLI
- Testing framework
- Scripts

---

### 📚 **DOCS FOLDER**

#### `docs/ARCHITECTURE.md`
- System architecture overview
- Component relationships
- Data flow diagrams
- Technology stack

#### `docs/API.md`
- API documentation
- Endpoint specifications
- Request/response formats
- Authentication

#### `docs/BLOCKCHAIN.md`
- Blockchain integration guide
- Smart contract documentation
- Transaction flows
- Wallet integration

#### `docs/GAME_MECHANICS.md`
- Game mechanics documentation
- Building system
- Resource management
- Progression system

#### `docs/DEPLOYMENT.md`
- Deployment guide
- Environment setup
- Build process
- Production configuration

---

### 🚀 **SCRIPTS FOLDER**

#### `scripts/build-zah.sh`
- Build script cho frontend
- Asset optimization
- Bundle creation
- Environment setup

#### `scripts/deploy-frontend-zah.sh`
- Frontend deployment
- Static file serving
- CDN configuration
- Environment variables

#### `scripts/deploy-program-duy.sh`
- Solana program deployment
- Network configuration
- Account setup
- Verification

---

## 🎯 **THỨ TỰ PHÁT TRIỂN KHUYẾN NGHỊ**

### Phase 1: Foundation (Tuần 1-2)
1. Setup project structure và dependencies
2. Tạo basic React app với routing
3. Setup backend server cơ bản
4. Tạo basic UI components

### Phase 2: Core Features (Tuần 3-4)
1. Implement authentication system
2. Tạo game engine core
3. Setup blockchain integration
4. Implement basic game mechanics

### Phase 3: Advanced Features (Tuần 5-6)
1. Complete game systems
2. Implement donation system
3. Add streaming integration
4. Optimize performance

### Phase 4: Polish & Deploy (Tuần 7-8)
1. UI/UX improvements
2. Testing và bug fixes
3. Performance optimization
4. Deployment và monitoring

---

## 📝 **GHI CHÚ QUAN TRỌNG**

- **ZAH**: Tập trung vào game engine, UI/UX, và backend core
- **DUY**: Tập trung vào blockchain, viewer features, và donation system
- **Collaboration**: Thường xuyên sync code và test integration
- **Testing**: Viết test cho mỗi component và system
- **Documentation**: Cập nhật docs khi có thay đổi
- **Performance**: Monitor và optimize performance thường xuyên

