[[POO]]

**Definições técnicas:**
- **Objeto** = Coisa material ou abstrata que pode ser percebida pelos sentidos e descrita por meio das suas características, comportamentos e estado atual.
- **Classe** = Define os atributos e métodos comuns que serão compartilhados por um objeto.

### Todo objeto têm atributos, métodos e estados!
- Todo objeto vêm de uma classe (molde);
```
Classe Caneta
	// Oque o objeto caneta têm
	
	modelo: Caractere
	cor: Caractere
	ponta: Real
	carga: Inteiro
	tampada: logico	
	
	// Oque o objeto faz
	
	Metodo rabiscar()
		Se (tampada) entao
			Escreva("ERRO")
		senao
			Escreva("Rabiscando...")
		FimSe
	FimMatodo
	
	Metodo tampar()
		tampada = verdadeiro
	FimMetodo
FimClasse
```
### Instanciar
- È quando você pega uma classe e gera um objeto a partir dela.

- **Como instanciar?**
```
// Para instanciar
(nome do objeto) = new (classe que vou utilizar)
// Para atribuir valor
(nome do objeto).(nome do atributo) = (valor)
// Para chamar um método
(nome do objeto).(nome do método)(atributo)
```

