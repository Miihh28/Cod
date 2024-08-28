</script>


<div id="txt">
<script type="text/javascript">document.write(startTime())</script>
</div>
2 - Inputs modificando após clique

<input type="text" value="usuario" onblur="if(this.value == ''){ this.value='usuario';}" onfocus="if(this.value == 'usuario'){ this.value='';}"/>
<input value="senha" onblur="if(this.value == ''){ this.value='senha'; this.type='text';}" onfocus="if(this.value == 'senha'){ this.value=''; this.type='password';}"/>
3 - Pegar a URL

<script>document.write(window.location.href);</script>
4 - Encontar uma palavra numa String (case sensitive)

<script>
var str = 'Terminal Root';

if(str.match(/Root/)){
  document.write('Encontrou');
}else{
	document.write('Palavra Não Encontrada');
}
</script>
