# InvertCadaPalabra
#Funcion que Invierte cada palabra una cadena
<HTML>
<HEAD>
<SCRIPT>
 
function revWord(str){
	 document.theForm.results.value = str.split("").reverse().join("").split(" ").reverse().join(" ");
}

</SCRIPT>
</HEAD>

<BODY>
<FORM name="theForm">
Introduzca una Frase:
<TEXTAREA name=inStr rows=5 cols=90>
</TEXTAREA>
<INPUT type=button value="Palabras Invertidas" onClick="revWord(document.theForm.inStr.value)";>
<INPUT type=button name="theButton" value="Limpiar Resultado" onClick='document.theForm.results.value=""';>
Resultado<br>
<TEXTAREA name=results rows=5 cols=90>
</TEXTAREA>
</FORM>  
</BODY>
</HTML>

