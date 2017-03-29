# NTUST_BigData_Course_MS_Feature_Importance (HW1)
## 哪些屬性對於惡意程式分類有效？

1. feature 306 (0.013313) section_names_header
2. feature 265 (0.009888) ent_p_8
3. feature 117 (0.009759) ent_q_diffs_var
4. feature 228 (0.008648) ent_q_diff_diffs_2_min
5. feature 226 (0.007732) ent_q_diff_diffs_2_median
6. feature 1638 (0.007393) Img4
7. feature 740 (0.007212) GetEnvironmentStrings
8. feature 1667 (0.005959) Img33
9. feature 877 (0.005929) IsValidCodePage
10. feature 800 (0.005830) __p__fmode

## 哪些屬性對於惡意程式分類無效？

1769. feature 681 (0.000000) GetMenuItemID
1770. feature 70 (0.000000) PCCTL_CONTEXT
1771. feature 457 (0.000000) __vbaRecAnsiToUni
1772. feature 1099 (0.000000) SetEnhMetaFileBits
1773. feature 1001 (0.000000) __vbaStrToUnicode
1774. feature 1101 (0.000000) GetEnhMetaFileBits
1775. feature 931 (0.000000) ImageList_Remove
1776. feature 382 (0.000000) __vbaPutOwner3
1777. feature 1007 (0.000000) GetBrushOrgEx
1778. feature 458 (0.000000) __vbaRecUniToAnsi
1779. feature 1110 (0.000000) __vbaStrI4
1780. feature 1111 (0.000000) __vbaVarCopy
1781. feature 1112 (0.000000) CopyEnhMetaFileA
1782. feature 1475 (0.000000) fstcwimul
1783. feature 1115 (0.000000) __vbaAryCopy
1784. feature 412 (0.000000) __vbaVarTstNe
1785. feature 423 (0.000000) __vbaVarZero
1786. feature 981 (0.000000) __vbaVarCat
1787. feature 868 (0.000000) GetKeyboardState
1788. feature 1049 (0.000000) ProcCallEngine
1789. feature 78 (0.000000) misc_market
1790. feature 1066 (0.000000) MethCallEngine
1791. feature 1037 (0.000000) ImageList_GetDragImage
1792. feature 449 (0.000000) GetFileTitleA
1793. feature 858 (0.000000) SetStretchBltMode
1794. feature 345 (0.000000) *invalid*
1795. feature 335 (0.000000) __vbaErase
1796. feature 1093 (0.000000) DeleteEnhMetaFile
1797. feature 1076 (0.000000) __vbaVar2Vec
1798. feature 349 (0.000000) __vbaAryVar
1799. feature 884 (0.000000) __vbaOnError
1800. feature 350 (0.000000) __vbaExitProc
1801. feature 667 (0.000000) AdjustWindowRectEx
1802. feature 431 (0.000000) __vbaStrFixstr
1803. feature 425 (0.000000) __vbaI4ErrVar
1804. feature 1020 (0.000000) ImageList_GetBkColor

## 用什麼方法可以幫助你決定上述的結論？

* 根據Random Forest演算法計算後, 可排列出對於分類惡意程式.

## 透過Python哪些套件以及方法可以幫助你完成上面的工作？

### 套件
1. numpy
2. matplotlib.pyplot
3. pandas
4. make_classification  (From sklearn.datasets)
5. ExtraTreesClassifier (From sklearn.ensemble)

### 演算法
* Random Forest
