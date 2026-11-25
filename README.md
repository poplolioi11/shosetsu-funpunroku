# 諸說紛紛錄（RB00003348） / Shosetsu funpun roku: Transcription Dataset

京都大學附屬圖書館富士川文庫藏一冊和裝中本抄本，館目原題為「諸説紛々録」。底本索書號 シ/227，登錄號 185240。 [館目](https://rmda.kulib.kyoto-u.ac.jp/item/rb00003348) · [館藏 IIIF](https://rmda.kulib.kyoto-u.ac.jp/iiif/metadata_manifest/RB00003348/manifest.json)

《諸說紛紛錄》是京都大學富士川文庫所藏的醫學抄本（RB00003348），館目著錄羽元胤著。卷首有〈治產後喘滿氣急說〉，全冊可見病症敘述、醫案及方藥，正文兼有漢文和日語。原件保留欄外墨書、朱標與獨立附條，可用於研究近世日本醫家如何編排病情、用方與治驗。本資料集對應館方 24 幅書影，其中 18 幅有正文，提供 JSON、TXT、TEI 和逐項校讀紀錄。第 22、23 幅同一右面只錄一次，第 23 幅左下另顯墨記保留位置。此版為 AI 校讀稿，原逐項校讀保留 886 項未解。人工全文二校待完成。

Shosetsu funpun roku is a medical manuscript held in the Fujikawa Collection at Kyoto University (RB00003348), catalogued under the author 羽元胤. It opens with a discussion of shortness of breath and fullness after childbirth and includes accounts of symptoms, cases, and prescriptions in Literary Chinese and Japanese. Marginal writing, red markings, and a loose handwritten slip offer evidence of how medical writers in early modern Japan organized observations, treatments, and their reported outcomes. The dataset maps to 24 official images, including 18 images bearing the main text, and provides JSON, TXT, TEI, and an item-level review ledger. The right page photographed in both images 22 and 23 is transcribed once. The ink mark newly visible at the lower left of image 23 retains its location. The AI-reviewed edition records 886 unresolved comparison items in the primary review. Full human collation is outstanding.

館目著者為羽元胤，抄者及抄寫年代未載。2016 年為館方數位化年度。

The catalogue attributes the work to 羽元胤. The copyist and copying date are unspecified. The library digitized the manuscript in fiscal year 2016.

第 4 幅另題《經驗方》。已查公開索引未見同作另一抄刊本、獨立影印、翻刻或完整文字。日本國立國會圖書館的館目連回同一京都底本。 [NDL 書目](https://ndlsearch.ndl.go.jp/books/R100000105-I000012686)

Image 4 bears the separate title 經驗方. The public sources searched yielded no independent manuscript or printed witness, separate facsimile, printed transcription, or complete machine-readable text. The National Diet Library catalogue entry links to this Kyoto witness.

[p004 左面大字題](https://rmda.kulib.kyoto-u.ac.jp/iiif/3/RB00003348%2FRB00003348_00004_0.ptif/full/2000,/0/default.jpg) · [p005 左面卷首與署名](https://rmda.kulib.kyoto-u.ac.jp/iiif/3/RB00003348%2FRB00003348_00005_0.ptif/full/2000,/0/default.jpg) · [p006 左外獨立墨書附條](https://rmda.kulib.kyoto-u.ac.jp/iiif/3/RB00003348%2FRB00003348_00006_0.ptif/full/2000,/0/default.jpg) · [p008 右面方藥文字](https://rmda.kulib.kyoto-u.ac.jp/iiif/3/RB00003348%2FRB00003348_00008_0.ptif/full/2000,/0/default.jpg) · [p022 右面正文末段](https://rmda.kulib.kyoto-u.ac.jp/iiif/3/RB00003348%2FRB00003348_00022_0.ptif/full/2000,/0/default.jpg) · [p023 左下翻角墨記](https://rmda.kulib.kyoto-u.ac.jp/iiif/3/RB00003348%2FRB00003348_00023_0.ptif/full/2000,/0/default.jpg)

## 資料與校讀

- `data/document.json` 保留歷史文字、原圖定位、疑讀及缺口。
- `data/text.txt`、`data/text.tei.xml` 及 sidecar 提供全文與逐文字單位對應。
- `data/review.json` 保留逐項校讀、未解 ID 及修訂採用狀態。
- `data/manifest.json` 與 `PACKAGE-SHA256SUMS.txt` 記錄固定發行檔案的雜湊。

固定底本有 24 幅官圖。正文自第 5 幅左面起，至第 22 幅右面止，跨 18 幅影像、34 個物理書面。第 6 幅左外另有一條墨書。第 23 幅右面與第 22 幅是同一末段，正文只錄一次。第 23 幅左下掀起紙角另顯墨記，保留其位置。

The fixed source comprises 24 official images. The main text spans 18 images and 34 physical page surfaces, from the left of image 5 to the right of image 22. Image 6 shows a separate handwritten slip outside the left page. Image 23 repeats the last passage seen on the right of image 22. The passage is transcribed once, while the ink mark visible on the lifted corner at lower left in image 23 retains its location.

初錄與第二路讀稿各以同一批固定原圖為據。Claude 完成第 1–24 幅初錄與第 1–6, 9–24 幅第二路讀稿。Claude 依原圖覆核 60 項比對。Codex 完成第 7–8 幅第二路讀稿。Codex 依原圖覆核 2556 項比對。全冊共有 2616 項比對，採用 14 項有原圖依據的修訂，最終保留 886 項未解。另有 481 項未套用的替代讀法，保存在逐項紀錄。JSON、TXT 和 TEI 的逐欄內容通過程式回讀，TEI 通過 P5 4.12.0 Relax NG 驗證。人工全文二校、專家審定與準確率量測尚待進行。

The two independent readings used the same fixed source images. Claude produced the first reading for images 1–24 and the second reading for images 1–6, 9–24. Claude reviewed 60 comparison items against the images. Codex produced the second reading for images 7–8. Codex reviewed 2556 comparison items against the images. The ledger records 2616 comparison items, 14 corrections supported by the images, and 886 remaining unresolved items. The ledger retains 481 alternate readings without applying them. Automated checks confirmed column-by-column agreement across JSON, TXT, and TEI. The TEI passed P5 4.12.0 Relax NG validation. Full human collation, expert assessment, and accuracy measurement are outstanding.

## 權利與引用

歷史原文、館藏影像、新增說明與資料編排依各自的權利條件處理。書影請由京都大學來源連結取用。 [權利說明](LICENSE.md)

曲宸宇（Chu, Chen-Yu）。2026。諸說紛紛錄（RB00003348） / Shosetsu funpun roku: Transcription Dataset。v0.1.0。資料集。 [固定發行](https://github.com/poplolioi11/shosetsu-funpunroku/releases/tag/v0.1.0) · [ORCID](https://orcid.org/0009-0003-9738-6914)
