# zen-puzzle
# ZenCPU Puzzle  
A minimal, interactive prototype of the **Zen‑Universe computation model**.  
This project implements:

- Zen Integer Arithmetic (Ƶ)
- Zen Gates (ADD / MUL / MAX / MIN / XOR)
- Zen Flow (value decay)
- Zen Circuit (wire routing)
- Zen Entropy (information heatmap)
- Interactive grid-based Zen CPU

All in a single HTML file.

---

## 🧠 What is ZenCPU?

**ZenCPU** is a cellular, integer‑based computational model inspired by the idea:

> “The universe does not compute with floating points.  
>  It computes with integers.”

Each cell holds a **Zen integer (0 to 2³²−1)**.  
Values flow, combine, decay, and generate entropy.  
Wires allow arbitrary routing between cells, forming circuits.

This prototype is a playground for exploring:

- integer‑only computation  
- emergent patterns  
- information flow  
- entropy dynamics  
- circuit behavior  
- early



This creates natural gradients and prevents runaway growth.

---

## 🔌 Zen Circuit (Wires)

Wires are directional connections:





A cell may receive multiple inputs.  
If more than two exist, Zen‑Universe rules apply:

- Use the **maximum** and **minimum** values  
- Discard the rest  

This produces stable, interpretable behavior.

---

## 🧪 Zen Entropy

Entropy is computed per cell:







A cell may receive multiple inputs.  
If more than two exist, Zen‑Universe rules apply:

- Use the **maximum** and **minimum** values  
- Discard the rest  

This produces stable, interpretable behavior.

---

## 🧪 Zen Entropy

Entropy is computed per cell:




This measures:

- information content  
- change  
- instability  
- computational “heat”  

Entropy is the foundation for future Zen‑Life experiments.

---

## 📁 Project Structure





No build tools, no dependencies.  
Just open `index.html` in a browser.

---

## 🛠 Future Extensions

This prototype is designed to evolve into:

- Zen‑Life (self‑replicating structures)
- Zen‑Compiler (circuit ⇄ expression)
- Zen‑Geometry (2D → 3D Zen space)
- Zen‑Flow Networks
- Zen‑Organisms

---

## 📜 License

MIT License  
Feel free to fork, modify, and explore.

---

## 🌌 Author

Created collaboratively with **むべさん**  
as part of the ongoing **Zen‑Universe** project.




# ZenCPU Puzzle  
Zen‑Universe の計算モデルを体験できる、  
**整数ベースのインタラクティブ CPU プロトタイプ**です。

このプロジェクトには以下が含まれます：

- Zen 整数演算（Ƶ）
- Zen ゲート（ADD / MUL / MAX / MIN / XOR）
- Zen フロー（値の減衰）
- Zen サーキット（配線）
- Zen エントロピー（情報量ヒートマップ）
- グリッド型 Zen CPU のインタラクション

すべて 1 つの HTML ファイルで動作します。

---

## 🧠 ZenCPU とは？

ZenCPU は次の思想に基づく計算モデルです：

> 「宇宙は浮動小数点で計算していない。  
>   宇宙は整数で計算している。」

各セルは **Zen 整数（0〜2³²−1）** を保持します。  
値は流れ、組み合わされ、減衰し、エントロピーを生みます。  
配線によってセル同士を自由に接続できます。

このプロトタイプは以下の実験に使えます：

- 整数のみの計算  
- パターンの自己生成  
- 情報の流れ  
- エントロピーの変化  
- 回路の振る舞い  
- Zen‑Life（生命構造）の基礎研究  

---

## 🎮 遊び方

### 1. ゲートを置く
ゲートボタン → セルをクリック。

### 2. IN / OUT
- **IN**：ランダムな Zen 値を生成  
- **OUT**：マーカー（現状は表示のみ）

### 3. 配線を引く
- セルを押したまま  
- 別のセルへドラッグ  
- マンハッタン経路で配線が生成  
- 配線は Zen 値を運ぶ

### 4. 表示モード切替
`VALUE` → Zen 値を色で表示  
`ENTROPY` → 情報量ヒートマップ

### 5. RANDOM IN
IN セルに新しい Zen 値を注入。

### 6. RESET
全リセット。

---

## 🌈 表示モード

### VALUE モード
- 赤：高い Zen 値  
- 青：低い Zen 値  
- 配線は運んでいる値で光る

### ENTROPY モード
- 赤：高い情報量  
- 青：低い情報量  
- エントロピー = log₂(value) + |Δvalue|

---

## 🧩 Zen ゲート

| ゲート | 内容 |
|--------|------|
| ADD | 飽和加算 |
| MUL | 正規化乗算 |
| MAX | 最大値 |
| MIN | 最小値 |
| XOR | ビット XOR |

すべて **整数演算のみ**で動作します。

---

## 🔥 Zen フロー

入力のないセルはゆっくり減衰します：

イグノーベル賞はもらえるぞ！



