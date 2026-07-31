## 🐾 PetApp3‑Kuro Edition  
ネザーランドドワーフ「Kuro」と過ごせる、軽量ポータブル版のAIペットアプリです。  
英語音声コマンドと顔検出に対応しています。

---

## 🎤 英語音声コマンド一覧（英語 → 状態）

Whisper による英語音声認識で、Kuro が n1〜p12 の状態に遷移します。

### 基本コマンド

| 英語コマンド | 状態 | 説明 |
|--------------|------|------|
| **play** | p1 | 遊びの反応（smile） |
| **sit** | n2 | おすわり |
| **sleep** | n3 | ねんね |
| **come here** | p1 | 近づく・遊びの反応 |
| **good boy / good girl** | p2 | 喜び（binky） |
| **I love you** | p12 | 特別な愛情表現 |
| **fetch** | p8 | ボールを持ってくる |
| **stand / stand up** | p10 | 立ち上がる |
| **bath / groom / brush** | p11 | お手入れ |

### その他のコマンド

| 英語コマンド | 状態 |
|--------------|------|
| **meal / food / hungry / eat** | p5 |
| **water / drink / thirsty** | p6 |
| **toilet / bathroom / pee / poop** | p7 |
| **house / go home / your house** | p9 |

---

## 🐇 名前呼び（Name Call）

Kuro の名前を呼ぶと、  
**p2（喜び・binky）** に遷移します。

---

## 😊 顔を見せる（FaceDetector）

カメラに **顔が映ると**、  
**p1（smile）** に遷移します。

※ PetApp3‑Taro / Frosty Edition とは異なり、  
　**笑顔判定ではありません。**

---

## 📦 Portable Edition

- Whisper 音声認識  
- 顔検出  
- Portable Python 同梱  
- インストール不要  

