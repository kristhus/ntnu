# Teorioppgaver øving 7
## Oppgave 1:
 - a) **Hva innebærer overlappende delproblemer? (5 %)**
  - At samme delproblem må løses flere ganger av en rekursiv algoritme
 - b) **Hvilket av disse problemene er hensiktsmessig å løse med dynamisk programmering? (5 %)**
  - Finne det n'te Fibonacci tallet
 - c) **Når er det hensiktsmessig å bruke dynamisk programmering? (5 %)**
  - Når delproblemene overlapper

## Oppgave 2:
 - a) **Hva blir T(1, 4) ? (10 %)**
  - 1
 - b) **Hva blir T(4, 3)?(Det kan være lurt å prøve å finne et system for ? svare p? oppgaven) (15 %)**
  - 10
 - c) **Finn et uttrykk som gjør deg i stand til å regne ut T(m, n). T(m, n) = ? (35 %)**
  - T(m-1, n) + T(m, n-1)

## Oppgave 3:
 - a) **N=4 p1 = 4, p2 = 9, p3 = 15, p4 = 18 (5 %)**
  - 19
 - b) **N=8 p1 = 4, p2 = 9, p3 = 15, p4 = 18, p5 = 21, p6 = 28, p7 = 31, p8 = 37 (5 %)**
  - 39
 - c) **Hvor mange delproblemer må man løse for å finne optimal løsning for stavkutting problemet? (5 %)**
  - Θ(n)Θ(n)

## Oppgave 4:
 - a) **W = 5v1 = 12, v2 = 10, v3 = 20, v4 = 15w1 = 2, w2 = 1, w3 = 3, w4 = 2(5 %)**
  - 37
 - b) **W = 740v1 = 18, v2 = 27,v3 = 51, v4 = 36, v5 = 24, v6 = 22, v7 = 29, v8 = 10, v9 = 24, v10 = 40w1 = 320, w2 = 301, w3 = 371, w4 = 296, w5 = 303, w6 = 359, w7 = 148, w8 = 275, w9 = 296, w10 = 395(5 %)**
  - 89