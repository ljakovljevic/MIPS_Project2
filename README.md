# MIPS_Project2
Broj epruveta = 15 (Lazar Jakovljević)
Vrednosti epruveta predstavljaju redni brojevi slova imena i prezimena u azbuci pa njihov ostatak pri deljenju sa 5, pa je to respektivno:
3, 1, 4, 1, 0, 1, 1, 2, 3, 3, 4, 2, 3, 0, 3
Maksimalna temperatura je broj slova u imenu i prezimenu puta 5, što je u mom slučaju 15 * 5 = 75,
Motor korišćen u projektu je step motor Nema34 - GM86HSA155-6004,
Temperaturni senzor je TMP36,
Driveri su TB6600,
Target epruveta je epruveta do koje treba da dodjemo kada se motor 1 zaustavi usled dostizanja maksimalne temperature,
Pun krug ima 360 stepeni a buduci da u projektu imamo 15 epruveta svaka uzima 24 stepena,
Posto korišćeni motor ima step od 1,8 stepeni potrebno mu je 13 koraka da bi presao sa jedne epruvete na sledću,
Uz pomoć tih podataka izračunavamo epruvetu na kojoj se nalazimo kada motor1 stane,
Nakon toga proverimo da li nam je kraći put do target epruvete na levo ili na desno i izracunamo koliko nam je koraka potrebno koristeći podatke u dužini stepa korišćenog motora,
Kada dodjemo do target epruvete palimo motor2 i odnosimo epruvetu.