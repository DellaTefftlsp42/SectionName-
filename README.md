# SectionName-
 If _ArraySearch($aSectionNames, $IWSC_SectionName) &lt; 0 Then    Return SetError(4, 0, 0)   EndIf   Local $aTempArray = StringSplit($IWSC_Comment, "|")   Local $IWSC_Index = _ArraySearch($aFileRead, "[" &amp; $IWSC_SectionName &amp; "]")   Local $aHolder[UBound($aFileRead) + UBound($aTempArray) - 1]
