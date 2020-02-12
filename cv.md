1. Verenich Aleksei
2. [earehon@gmail.com](mailto:earehon@gmail.com) or [telegram: earehon](https://t.me/earehon)
3. "What I want" - It is a good question. 
4. Basic knowledge JS, CSS, HTML, PHP, SQL
5. Code example

```javascript
function multiply(first, second) {
	let a = first.split('').reverse();
	let b = second.split('').reverse();
		
	let comp = [];
		
	for (let i = 0; i < a.length+b.length; i++)
	{
	comp[i] = 0;
	}
		
	for (let i = 0; i < a.length; i++){
		for (let j = 0; j < b.length; j++){
			comp[i+j] += (a[i] * b[j]) % 10;
			comp[i+j+1] += Math.floor((a[i] * b[j]) / 10);
				
			if(comp[i+j] >= 10){
			let temp = comp[i+j];
			comp[i+j] %= 10;
			comp[i+j+1] += Math.floor(temp / 10);
		}
	}
}
		
if(comp[comp.length-1] == 0)
	comp.pop();

return comp.reverse().join('');
}
```

6. Since 2014 development of simple sites on php, css and html. Work with wordpress, latex. Administration and support of a database on 1C
7. Graduated from BrSU 2014 with a degree in Applied Mathematics.
8. Use English only on online games and watch Top Gear on English with sub.
