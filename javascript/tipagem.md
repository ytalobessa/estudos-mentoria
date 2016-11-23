##Tipagem Dinâmica Javascript
O Javascript tem a tipagem dinâmica, é muito flexível quando se trata de usar uma única variável que tenha qualquer tipo de valor, seja “string” ou number. Também facilita para prototipação rápida, diferente de uma tipagem estática, pois a tipagem dinâmica tem uma sintaxe mais fácil.

Podemos ver essa flexibilidade em um trecho de código do livro “You Don't Know JS: Up & Going”:

	var amount = 99.99;
	amount = amount * 2;
	console.log( amount );      // 199.98
	// convert `amount` to a string, and
	// add "$" on the beginning
	amount = "$" + String( amount );
	console.log( amount );      // "$199.98"

Geralmente uma tipagem dinâmica torna a detecção de erros mais difícil, pois são percebidos quando o programa está em execução, o que é preocupante em projetos grandes.

