# Actividad-3
package Actividad3;

import java.security.SecureRandom;

public class Main {

    public static void main(String[] args) {

        Deck deck = null;

        for(int i = 0; i < 52; i++) {

            SecureRandom numero = new SecureRandom();

            deck = new Deck(leerDatos(), numero.nextInt(3));

        }

        deck.shuffle();

        deck.head();

        deck.pick(6);

        deck.hand();

    }

    public static Card leerDatos() {

        SecureRandom aleatorio = new SecureRandom();

        String[] palo = {"treboles", "corazones", "picas", "diamantes"};
        String[] color = {"rojo", "negro"};
        String[] valor = {"2", "3", "4", "5", "6", "7", "8", "9", "10", "A", "J", "Q", "K"};

        int opcion1 = aleatorio.nextInt(5);

        int opcion2 = aleatorio.nextInt(4);

        int opcion3 = aleatorio.nextInt(15);

        return new Card(palo[opcion1], color[opcion2], valor[opcion3]);

    }

}
