# VarGetType
EndFunc Func _CW($Whatever1, $Whatever2 = @ScriptLineNumber, $Whatever3 = @error, $Whatever4 = @extended)     ConsoleWrite("(" &amp; $Whatever2 &amp; ") :" &amp; " /Current@Error:" &amp; $Whatever3 &amp; " /Current@Extended:" &amp; $Whatever4 &amp; " /VarGetType:" &amp; VarGetType($Whatever1) &amp; " /Value:" &amp; $Whatever1 &amp; @CRLF) EndFunc
