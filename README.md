# EAN-13, EAN-8 & UPC-A Barcode Generator

Excel だけで JAN（EAN-13 / EAN-8）と UPC-A バーコードを一括作成するツールです。生成は PC 上で完結し、外部にデータを送りません。

**買う（note・¥1,000）:** [note.com/ktech_dev/n/nf2fc9e3e7bc0](https://note.com/ktech_dev/n/nf2fc9e3e7bc0)  
**見る（LP）:** [jancode-psi.vercel.app](https://jancode-psi.vercel.app/)

[English](#english) | [日本語](#japanese)

---

<a name="english"></a>
## English

Create scanner-ready EAN-13, EAN-8, and UPC-A barcodes in Excel. No web upload.

**Terminology:** EAN-13 carries a GTIN-13, EAN-8 carries a GTIN-8, and UPC-A carries a GTIN-12. In Japan, EAN-13 and EAN-8 are commonly called JAN codes.

**[Buy on note — ¥1,000](https://note.com/ktech_dev/n/nf2fc9e3e7bc0)** · **[Landing page](https://jancode-psi.vercel.app/?lang=en)**

This GitHub repo is the landing page only. The workbook is **not** in this repository. You get it from note after purchase.

### What you get

* `.xlsm` (current Excel) and `.xls` (legacy Excel)
* English and Japanese manuals
* Batch generation (about 1,000 items)
* 13-digit EAN-13, 12-digit UPC-A, 8-digit EAN-8
* Check digit verification
* Error highlighting for bad codes
* Fully offline VBA — no network calls

### Requirements

* Windows 10 / 11
* Excel 2016 or later (32-bit and 64-bit)
* **Not supported:** Mac Excel, iPad, Google Sheets, LibreOffice

### Privacy

Barcodes are generated inside Excel on your PC. This site does not collect your barcode lists.

---

<a name="japanese"></a>
## 日本語

スキャナが迷わない JAN / EAN / UPC-A バーコードを、Excel だけで一括作成します。

**[note で購入 — ¥1,000](https://note.com/ktech_dev/n/nf2fc9e3e7bc0)** · **[紹介ページ](https://jancode-psi.vercel.app/)**

この GitHub は紹介サイト（LP）の置き場です。**Excel 本体はこのリポジトリに入っていません。** 購入後に note からダウンロードします。

### 届くもの

* `.xlsm`（現行 Excel）と `.xls`（旧形式）
* 英語・日本語マニュアル
* 一括作成（約 1,000 件）
* 13桁のJAN、12桁のUPC-A、8桁の短縮JAN
* チェックデジットの確認
* 誤りを青で検知
* 完全オフライン（外部通信なし）

### 動作環境

* Windows 10 / 11
* Excel 2016 以降（32bit / 64bit）
* **非対応:** Mac 版 Excel、iPad、スプレッドシート、LibreOffice など

### プライバシー

生成は PC 上の Excel（VBA）内で完結します。この LP は商品番号リストを保存しません。

---

## このリポジトリ

静的な紹介ページです。

```
index.html
assets/barcode.mp4
images/ogp-main.jpg
```

技術メモ: [k-tech-jancode-docs](https://github.com/crossbeat461-a11y/k-tech-jancode-docs)  
Studio: [k-tech-lab.vercel.app](https://k-tech-lab.vercel.app/)  
Support: [Buy Me a Coffee](https://buymeacoffee.com/k_tech_studio)

免責: 現状有姿です。利用は自己責任でお願いします。詳細は [LP](https://jancode-psi.vercel.app/) にもあります。

© K-Tech Studio
