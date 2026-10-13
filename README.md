# 大明永曆三十一年大統曆 · Bodleian Sinica 88

本資料集依牛津大學 Bodleian Libraries 所藏 Sinica 88 的 1677 年藍印刊本，整理原刊漢文、紀年表、十二個月的日期與日用欄、年神方位圖文字及年曆摘要。官方 IIIF 共 16 個數位畫布。保留館方畫布次序、來源定位、原字與未解缺損，提供 UTF-8 純文字、JSON、TEI XML 及疑字清單。

**品質狀態：AI 影像初錄及部分獨立覆核勘誤；未經專家認證。** 16 幅原圖的獨立先讀已保存；本版完成第 1、2、7、15、16 幅的來源裁定，其他 11 幅的差異仍待裁定。全書獨立二校、人工雙校及同儕審查尚未完成。已通過的格式檢查不代表原字全部正確。實際範圍以 `review-scope.json`、`coverage.json`、`uncertainties.json` 和 `VALIDATION.json` 為準。

v0.1.1 涵蓋 16 個畫布、814 個閱讀單元及 355 個日條，另保留 121 個已查看的空單元。原文編碼共 13,983 個 Unicode 碼點（含換行與占位）；280 個 `□` 中，209 個標記單字字位，71 個標記長度未詳的文段。這些數值不能換算為全書未知字數或辨識準確率。

本版保留初版單位 ID，補入紀年表下方一個漏錄的實體欄，記錄 65 項文字或疑字資料變更，並修正 31 個下欄定位標籤。原圖的「京直」不展開為「驚蟄」；不確定的大／太、圖內細字等仍保留疑字。第 12 幅由兩位獨立讀圖工作分段覆蓋，不將其中一位冒稱為讀完整幅。詳見 `corrections.json` 與 `review-scope.json`；初版 tag 與資料包保留。

This dataset transcribes the original Chinese printed content of the 1677 blue-print *Daming Yongli 31 Datong Calendar*, Bodleian Sinica 88. It retains source order, image references, reading units and unresolved readings. Version 0.1.1 contains source-adjudicated corrections for canvases 1, 2, 7, 15 and 16. All 16 canvases have saved independent source-first readings, but full collation and final adjudication remain incomplete. There is no expert certification. Machine-readable validation checks format and consistency, not historical or palaeographic accuracy.

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
| `review-scope.json` | 已完成與待裁定的覆核範圍 |
| `PROVENANCE.md` / `LICENSE.md` | 來源、責任與分層權利 |
| `CITATION.cff` | 引用資料 |

單位 ID 與欄位標籤可用於引用。`□` 表示未解或缺損；未必恰好缺一個字，應一併讀其 uncertainty 註記。offset 以 Unicode 碼點計數，從 1 起算。區域定位使用固定下載影像的實際像素；部分定位只達半面或欄，不是逐字框。原圖 URI 的來源尺寸與 manifest 畫布尺寸可不同。

原刊漢文範圍包含圖中文字。圖形另以來源 URI、區域與現代描述交代，不宣稱已向量重建圖式。後加英文字批註因权利未核排除公開文字；館藏鉛筆編號和數位尺規亦不屬原刊漢文。來源影像、裁片、縮圖及館方標誌不在本公開包內。

本專案不以曆法推算、語意流暢或其他版本修正取文本。原印可能本有訛字；確切讀字與校訂建議應分開。沒有標疑也不等於已證明正確。

## 授權與引用

1677 原刊歷史文字依本輪年代與既刊證據判斷已屆一般保護期限，不加新的專案限制；此判斷不代表全球法律保證或館方特許。本專案有著作權的新編資料結構、定位、註釋與文件採 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)。館方影像另採 [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)，未隨資料再散布。詳見 `LICENSE.md`。

維護與資料發布：一卦 / [poplolioi11](https://github.com/poplolioi11)，公開網站 [yigua.art](https://yigua.art/)。歷史作者未詳。引用時請註明資料版本、來源館藏與所用單位。本版尚無已發布 Zenodo DOI，請先引用 GitHub 版本頁。初版 DOI `10.5281/zenodo.23336201` 僅保留，尚未發布；不能將它冒用為本版 DOI。

修訂請參照 `CONTRIBUTING.md`，提供來源畫布、單位與原圖證據。详细處理程式、提示及完整工作紀錄留存本機，未納入本公開包。
