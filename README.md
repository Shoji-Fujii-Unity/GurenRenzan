# 紅蓮連斬 -Guren Renzan-

## 対応言語 / Language Support
このゲームは日本語と英語に対応しています。
タイトル画面の Language / 言語切替ボタンから切り替えることができます。

この README も日本語と英語の両方に対応しています。

---

## 日本語

### 概要
紅蓮連斬 -Guren Renzan- は、Canvas 2D を使用したブラウザ型 2D サバイバルアクションゲームです。

### 必要ファイル
- index.html
- README.md

このゲームはビルド処理が不要です。
index.html をそのままブラウザで開くだけで動作します。
外部 JavaScript ライブラリは使用していません。

### 起動方法
1. index.html をブラウザで開きます。
2. タイトル画面から操作を行います。
3. 画面は横向きで遊ぶことを推奨しています。
4. スマホでは横向きに回転してプレイしてください。

### PC 操作
- 移動: WASD または矢印キー
- 通常攻撃: J、Z、Space
- 必殺技: K、X
- 回避: Shift、U、L
- 一時停止: Esc または P

### スマホ操作
- 画面左側: 仮想スティックで移動
- 画面右側: 攻撃、必殺、回避ボタン
- 右上の一時停止ボタン: Pause

### セーブデータ
- セーブデータは端末内のブラウザ localStorage に保存されます。
- 進行状況はステージ解放情報、ベスト記録、キャラクター成長値などを保存します。
- 同じ端末、同じブラウザ、同じローカル環境であれば続きからプレイできます。
- ブラウザのキャッシュやストレージを消去するとセーブデータは失われます。
- 端末間でのセーブ同期機能はありません。

### 音量
- サウンドは ON / OFF を切り替えることができます。
- タイトル画面の Sound / サウンド ボタンから変更できます。

### 画面表示
- スマホ向けに横向き画面を前提としています。
- 縦向き画面の場合は、横向きへ回転してください。
- 一部のブラウザでは自動回転が効かない場合があります。その場合は手動で画面を横向きにしてください。
- 画面が横長にならない場合、ゲームは進行しない場合があります。

### ゲーム内容
- ステージ数は多数用意されています。
- 敵の種類は多数用意されています。
- ボスキャラクターはステージごとに複数種類存在します。
- プレイヤーはステージを攻略すると成長します。
- 必殺ゲージを消費して強力な全体攻撃を放つことができます。
- 回避行動には無敵時間があります。
- 連続攻撃でコンボが上昇し、スコアや演出に影響します。
- 敵の種類によって射撃、突進、瞬間移動、範囲攻撃、盾ガードなどの行動特性があります。

### 技術情報
- 2D グラフィックスには Canvas 2D API を使用しています。
- Three.js は使用していません。
- 追加のライブラリや画像ファイルは必要ありません。
- すべてのゲーム処理は index.html 内に含まれています。

### 動作環境
- 推奨ブラウザ: Chrome, Edge, Firefox, Safari の最新安定版
- 対応機種: PC ブラウザ、スマートフォンブラウザ
- オフライン動作: 対応しています。外部ファイルを読み込まないため、index.html 単体で動作します。
- ローカルサーバーを使わなくても動作する想定ですが、ブラウザの仕様によってはローカルサーバーでの提供が安全です。

### ローカルサーバーで遊ぶ場合
ブラウザの制限によっては、index.html を直接開くと正常に動作しない場合があります。
その場合は、適当な静的ファイルサーバーで index.html のあるフォルダを配信してください。
ローカルサーバーを使う場合は、ファイル名が index.html であれば http://localhost:8000/ などのような URL で開けます。

### 注意点
- 画面が黒いまま表示されない場合は、ブラウザのリロードを行ってください。
- セーブが反映されない場合は、ブラウザのストレージ設定を確認してください。
- スマホで動作が重い場合は、ブラウザの表示品質を下げる設定や省電力モードを確認してください。
- ゲーム内 UI は横向きで遊ぶことを前提に設計されています。
- ゲーム中にブラウザの画面回転を無効にしている場合は、手動で横向きにしてください。

---

## English

### Overview
Guren Renzan - Crimson Chain is a browser-based 2D survival action game made with Canvas 2D.

### Required Files
- index.html
- README.md

No build step is required.
Open index.html directly in a browser.
No external JavaScript library is used.

### How to Start
1. Open index.html in a browser.
2. Start the game from the title screen.
3. Play in landscape mode.
4. On smartphones, rotate your device to landscape.

### PC Controls
- Move: WASD or Arrow Keys
- Attack: J, Z, Space
- Special: K, X
- Dash: Shift, U, L
- Pause: Esc or P

### Mobile Controls
- Left side of screen: virtual joystick for movement
- Right side of screen: Attack, Special, Dash buttons
- Upper-right button: Pause

### Save Data
- Save data is stored locally in the browser's localStorage.
- The game saves stage unlocks, best scores, character growth, and related progress.
- You can continue playing on the same device, browser, and local environment.
- Deleting browser storage or cache may erase save data.
- There is no cloud sync or cross-device save synchronization.

### Sound
- Sound can be turned ON or OFF.
- Use the Sound button on the title screen.

### Screen Display
- The game is designed for landscape mode.
- If the screen is portrait, rotate the device to landscape.
- Some browsers may not automatically rotate. In that case, rotate manually.
- If the screen is not landscape, the game may not progress.

### Game Content
- Many stages are available.
- Many enemy types are available.
- Multiple boss characters appear across stages.
- The player grows stronger by clearing stages.
- The special gauge can be consumed to unleash powerful area attacks.
- Dash includes invincibility frames.
- Combos increase during continuous attacks and affect score and presentation.
- Enemies can shoot, dash, teleport, slam, or shield according to their type.

### Technical Information
- 2D graphics use the Canvas 2D API.
- Three.js is not used.
- No additional libraries or image files are required.
- All game code is contained inside index.html.

### Environment
- Recommended browsers: latest stable Chrome, Edge, Firefox, or Safari
- Supported devices: PC browsers and mobile browsers
- Offline support: supported. The game works from index.html alone because it does not load external files.
- It is intended to work without a local server, but serving the folder through a local static server is safer because of browser restrictions.

### Running Through a Local Server
Depending on browser restrictions, opening index.html directly may not work correctly.
In that case, serve the folder containing index.html with any static file server.
Because the file is named index.html, you can open it with an address such as http://localhost:8000/ when served locally.

### Notes
- If the screen stays black, reload the page.
- If saves are not reflected, check your browser storage settings.
- If performance is slow on mobile, check browser graphics settings or power-saving mode.
- The game UI is designed for landscape play.
- If browser screen rotation is disabled, rotate the device manually.