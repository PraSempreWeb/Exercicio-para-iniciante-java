# Fala Devs :vulcan_salute:

## Exercicio para iniciante - java  
## Array (Jogo de Cartas) :black_joker:

### Programa ao se executado, mostrará a face da carta e seu Nipe. Bora jogar!  

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
