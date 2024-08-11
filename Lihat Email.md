```
javascript: (() => { const documentHTML = document.documentElement.outerHTML; const matches = documentHTML.matchAll(/[\w.+=~-]+@[a-zA-Z0-9-]+(?:\.[a-zA-Z0-9-]+)*/g);%20const%20flatMatches%20=%20Array.from(matches).map((item)%20=%3E%20item[0]);%20const%20uniqueMatches%20=%20Array.from(new%20Set(flatMatches));%20if%20(uniqueMatches.length%20%3E%200)%20{%20const%20result%20=%20uniqueMatches.join(%27\n%27);%20alert(result);%20}%20else%20{%20alert(%27Alamat%20email%20tidak%20ditemukan!%27);%20}%20})();
```
