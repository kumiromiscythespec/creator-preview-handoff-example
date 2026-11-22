# 納品明細の改ページと画像一覧を試す

同じ出荷IDの架空21明細を、A4の2ページに分けた見本です。Excelで改ページを確認し、2枚の帳票画像から共有用の一覧PNGを作れます。

| ファイル | 内容 |
| --- | --- |
| `shipping-detail-pagination-trial.xlsx` | 架空21明細が入った改ページ用の固定試用版 |
| `shipping-template-print-page-1.png` | 1ページ目の20明細を載せた帳票画像 |
| `shipping-template-print-page-2.png` | 2ページ目の残り1明細を載せた帳票画像 |

## Excelで2ページを照合する

1. ZIPを展開し、デスクトップ版Excelで試用版XLSXを開きます。「納品明細」シートの出荷ID欄 `B4` に `000017`、ページ番号欄 `E4` に `1` を入力します。A4の印刷プレビューに20明細が載ることを確認します。
2. `E4` を `2` に切り替えます。同じ出荷IDで残りの1明細が表示されることを確認します。各ページの出荷IDと先頭・末尾の明細を、対応する見本画像と照合します。

## 2ページを1枚のPNGに並べる

1. 商品プレビュー一覧工房を開き、**納品明細の印刷見本で一覧PNGを作る** を選びます。自分で並べる場合は、画像の選択欄で同梱のPNG2枚を選び、2列に設定して **一覧PNGを作る** を選びます。[納品明細の画像で試す](https://preview-sheet-studio-1111.crisp-llama-2628.chatgpt.site/?example=shipping)
2. 20明細のページが左、残り1明細のページが右にあることを確かめます。必要ならラベルを直して作り直し、**PNGを保存** を選びます。保存したファイルを開き、見出しとページの順番が分かる状態で共有できるか確認します。

手元の明細を貼り付けて使う場合は、同じ運営者がココナラで販売する500円のExcelテンプレートの仕様を確認できます。[販売版とA4の見本](https://shipping-csv-preflight.crisp-llama-2628.chatgpt.site/template/#print-preview)

---

# Practice delivery-statement pagination

This exercise uses 21 fictional line items for a single shipment. Compare the two A4 pages in the free Excel workbook, then arrange the supplied print images into one shareable PNG.

## Check the pages in Excel

1. Extract the ZIP and open `shipping-detail-pagination-trial.xlsx` in desktop Excel. On the Japanese **納品明細** (delivery statement) sheet, enter shipment ID `000017` in `B4` and page number `1` in `E4`. Check that the A4 print preview contains 20 line items.
2. Change `E4` to `2` and verify that the same shipment ID has one remaining item. Compare the first and last entries on each workbook page with the corresponding supplied PNG.

## Build a two-page preview sheet

1. Open Preview Sheet Studio and choose **Make a PNG from delivery statement samples**. To arrange the downloaded files yourself, choose the two supplied PNGs, select two columns, and choose **Generate preview PNG**. The generator interface is available in English. The sample print pages and workbook are in Japanese. [Open the delivery-statement example](https://preview-sheet-studio-1111.crisp-llama-2628.chatgpt.site/?lang=en&example=shipping)
2. Check that page 1 with 20 items is on the left and page 2 with one item is on the right. Edit the labels if useful, generate again, and choose **Save PNG**. Reopen the saved file to check whether a recipient can distinguish the two pages.

The operator also offers a ¥500 template for pasting in your own line items. The linked guide describes what it supports and shows both A4 pages. [View the template and print example](https://shipping-csv-preflight.crisp-llama-2628.chatgpt.site/template/#print-preview)
