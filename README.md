<h1>Como Usar:</h1>

<h2>Defina o Objeto</h2>
<pre>
$varObject: (
    keyName1: value1,
    keyName2: value2
);
@include object-set(nameKey, $varObject);
</pre>

<h2>Recuperando Valores</h2>
<pre>
.seletor{
    prop: object-get(nameKey, $keyName);
}
</pre>