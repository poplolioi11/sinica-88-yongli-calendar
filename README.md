# 大明永曆三十一年大統曆 · Bodleian Sinica 88

本資料集依牛津大學 Bodleian Libraries 所藏 Sinica 88 的 1677 年藍印刊本，整理原刊漢文、紀年表、十二個月的日期與日用欄、年神方位圖文字及年曆摘要。官方 IIIF 共 16 個數位畫布。保留館方畫布次序、來源定位、原字與未解缺損，提供 UTF-8 純文字、JSON、TEI XML 及疑字清單。

**品質狀態：全書 AI 影像校對，保留未解讀字；未經專家認證。** 官方 16 幅原圖皆有獨立先讀、全單元比對及來源裁定。人工雙校、專家覆核及同儕審查尚未執行。格式檢查不代表原字全部正確，也不保證所有印字均已辨明。實際範圍以 `review-scope.json`、`coverage.json`、`uncertainties.json` 和 `VALIDATION.json` 為準。

v0.1.2 涵蓋 16 個畫布、815 個閱讀單元及 355 個日條，另保留 122 個已查看的空單元。原文編碼共 13,827 個 Unicode 碼點（含換行與占位）；387 個 `□` 中，269 個標記單字字位，118 個標記長度未詳的文段。這些數值不能換算為全書未知字數或辨識準確率。

本版保留初版單位 ID，補入紀年表下方一個漏錄實體欄及一個原印空格；空格不補第三十日。初版至本版有 340 項文字或疑字資料變更、68 項定位或閱讀順序變更，另列兩個新增單元。小注歸屬依印字與日期欄線核對，訂正後維持原圖閱讀序。原圖的「京直」不展開為「驚蟄」；月頁小寒十三與年表十二等原印差異分別保留。不能定字的初錄確讀改列疑字，因此占位標記數增加。第 12 幅由兩位獨立讀圖工作分段覆蓋，不將其中一位冒稱為讀完整幅。詳見 `corrections.json` 與 `review-scope.json`；初版與部分勘誤版 tag、資料包均保留。

This dataset transcribes the original Chinese printed content of the 1677 blue-print *Daming Yongli 31 Datong Calendar*, Bodleian Sinica 88. Version 0.1.2 completes AI source-first independent reading, unit comparison and source adjudication across all 16 canvases, with unresolved readings retained. It preserves original glyph choices and printed discrepancies rather than reconciling them through calendar calculations. Canvas 12 was read in separate portions by two readers. There is no human double-collation, expert certification or peer review. Validation checks format and consistency, not historical or palaeographic accuracy.

## 底本與既有研究

- [Digital Bodleian 原件](https://digital.bodleian.ox.ac.uk/objects/2d355165-8334-44e2-b51e-3c37245bea93/)
- [官方 IIIF manifest](https://iiif.bodleian.ox.ac.uk/iiif/manifest/2d355165-8334-44e2-b51e-3c37245bea93.json)
- [Serica 書目](https://serica.ie/SericaProject/data/558-568.html)
- [Y. T. Liu 的同版曆法表格](https://ytliu0.github.io/ChineseCalendar/N1677_Zheng_simp.html)與[清、南明、鄭氏曆法比較研究](https://ytliu0.github.io/ChineseCalendar/QingSouthernMingZheng_calendars.html)

同版的朔閏、節氣、紀年已有部分結構化文字，核心曆法已有比較研究。本專案提供逐日日用等欄及可定位的資料，不宣稱全球首度數位化、沒有既有文字或零研究；不取用現代整理稿代替原圖讀字。

封面明言「本藩」「命官考訂刊行」。具體編者未署；這支持藩署刊曆，不能直接改稱中央官署、司天監或欽天監編纂。書名中的永曆三十一年為 1677 年紀年。16 個畫布不是 16 葉的物理頁數主張。

## 檔案與使用

| 檔案 | 用途 |
| --- | --- |
| `sinica-88.json` | 固定底本、畫布、閱讀單位與逐項疑字 |
| `sinica-88.txt` | UTF-8 原文及導航標記；導航不屬底本文字 |
| `sinica-88.tei.xml` | TEI P5，表面、來源區域與文字單位對應 |
| `schema.json` | 本資料集的 JSON Schema |
| `uncertainties.json` | 未解字與缺損位置、候選及缺損長度狀態 |
| `coverage.json` | 指定範圍、完成狀態與統計 |
| `VALIDATION.json` | 格式、來源及跨格式一致性驗證摘要 |
| `corrections.json` | 初版至本版的文字、疑字與定位變更 |
| `review-scope.json` | 完成的覆核範圍及未執行的專家審查 |
| `PROVENANCE.md` / `LICENSE.md` | 來源、責任與分層權利 |
| `CITATION.cff` | 引用資料 |

單位 ID 與欄位標籤可用於引用。`□` 表示未解或缺損；未必恰好缺一個字，應一併讀其 uncertainty 註記。offset 以 Unicode 碼點計數，從 1 起算。區域定位使用固定下載影像的實際像素；部分定位只達半面或欄，不是逐字框。原圖 URI 的來源尺寸與 manifest 畫布尺寸可不同。

原刊漢文範圍包含圖中文字。圖形另以來源 URI、區域與現代描述交代，不宣稱已向量重建圖式。後加英文字批註因权利未核排除公開文字；館藏鉛筆編號和數位尺規亦不屬原刊漢文。來源影像、裁片、縮圖及館方標誌不在本公開包內。

本專案不以曆法推算、語意流暢或其他版本修正取文本。原印可能本有訛字；確切讀字與校訂建議應分開。沒有標疑也不等於已證明正確。

## 授權與引用

1677 原刊歷史文字依本輪年代與既刊證據判斷已屆一般保護期限，不加新的專案限制；此判斷不代表全球法律保證或館方特許。本專案有著作權的新編資料結構、定位、註釋與文件採 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)。館方影像另採 [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)，未隨資料再散布。詳見 `LICENSE.md`。

維護與資料發布：一卦 / [poplolioi11](https://github.com/poplolioi11)，公開網站 [yigua.art](https://yigua.art/)。歷史作者未詳。引用時請註明資料版本、來源館藏與所用單位。本版 DOI 為 [10.5281/zenodo.23339992](https://doi.org/10.5281/zenodo.23339992)，全版本 DOI 為 [10.5281/zenodo.23336200](https://doi.org/10.5281/zenodo.23336200)。初錄版已封存為 [10.5281/zenodo.23336201](https://doi.org/10.5281/zenodo.23336201)。本版 DOI 預留於製包時，正式登記與檔案狀態以 Zenodo 公開紀錄為準；初版 DOI 不能冒用為本版 DOI。

修訂請參照 `CONTRIBUTING.md`，提供來源畫布、單位與原圖證據。详细處理程式、提示及完整工作紀錄留存本機，未納入本公開包。
