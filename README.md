# 構成的完全証明：カタラン予想 / Constructive Proof of the Catalan Conjecture

このリポジトリは、カタラン予想（ミハイレスクの定理）に対する構成的完全証明を収録しています。

## 🔍 問題概要

カタラン予想とは、次の等式を満たす自然数解が唯一であることを主張します：

> \( x^a - y^b = 1 \) の整数解で \( a, b > 1 \) を持つものは、唯一 \( 3^2 - 2^3 = 1 \)

## ✅ 証明の特徴

- 構成的指数間隔理論とA型素数モデルを導入
- 素因数分解の差分構造に基づく一意性の保証
- 1差を許す指数組における構成的除去関数の適用
- 補題・定義・定理の明示による形式的構成展開

## 📂 ディレクトリ構成

```
.
├── main.tex
├── sections/
│   ├── introduction.tex
│   ├── power_difference.tex
│   ├── unique_case_filter.tex
│   ├── constructive_bounds.tex
│   ├── theorem_proof.tex
│   └── conclusion.tex
├── README.md
├── LICENSE
├── compile.sh
└── .gitignore
```

## 🧠 証明構成法（LaTeX展開）

- \( x^a = y^b + 1 \) となる指数差分の構成的分析
- 除去関数と指数密度制約により、唯一解以外を形式排除
- ミハイレスク定理と一致する構成的結論を導出

## 🌐 GitHub Topics（推奨）

```
math
number-theory
catalan-conjecture
mihailescu-theorem
constructive-mathematics
power-equations
diophantine-equations
latex
arxiv-compatible
```

## ✍️ ライセンス

本リポジトリは [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) に従って公開されています。

---
_この証明は、AIと人間の協働による構成的数論の確立に基づいて実施されました。_
