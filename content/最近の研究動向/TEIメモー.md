- tei_all_ja.rngは同じフォルダに入れることで、TEI の修正ができます。
- 選択したテキストをCommand+Eで囲むと、素早く対応するタグを追加できます。

## back名前の引用

`<persName corresp="#souseki"> 金之助</persName>`

```
<back>
<listPerson>
<person xml:id="souseki">
<persName>夏目漱石</persName>
<persName>夏目金之助</persName>
<idno type="VIAF">
http://viaf.org/viaf/56614190
</idno>
</person>
<person xml:id="2">
<persName>鏡どの</persName>
</person>
</listPerson>
</back>
```


## choice

`人ノ言フ<choice><orig>ヿ</orig><reg>コト</reg></choice>ヲ善ヒ加減ニ聞テハイケマセン。`

在古典日语和一些旧的印刷物中，**“ヿ” (U+30FF)** 是汉字“事”的一个**略写、草书或异体字**，在阅读时读作“こと (koto)”。

![[Pasted image 20250621123929.png]]