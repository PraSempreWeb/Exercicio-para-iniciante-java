# Fala Devs :vulcan_salute:

## Exercicio para iniciante - java  
## Array (Jogo de Cartas) :black_joker:

### Programa ao se executado, mostrará a face da carta, seu Nipe. Bora jogar!  

[![Linkedin Badge](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white&link=https://www.w3schools.com/java/default.asp)](https://www.w3schools.com/java/default.asp)

```
public class JogoCartas {
	public static void main(String[] args) {
		
		String[] nipes = {"Paus", "Ouro", "Espada", "Copas"};
		String[] faces = {"Az", "2", "3", "4", "5", "6", "7", "8", "9", "10", "Dama", "Valete", "Rei"};
		
		String nipe = nipes[(int) (Math.random() * 4)];
		String face = faces[(int) (Math.random() * faces.length)];
		
		System.out.println(face + " de " + nipe);
	}
}
```
