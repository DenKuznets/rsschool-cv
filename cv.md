### [rsschool-cv](https://DenKuznets.github.io/rsschool-cv/)

***

# Denis Kuznetsov

### Frontend-developer

<img src="avatar-small.png" alt="avatar" width="200"/>

---

## Contact information

Phone +79969191309

E-mail: denis.kyznecov@gmail.com

Telegram: [@DenKuznets](https://t.me/DenKuznets)

[Personal Website](https://denkuznets.vercel.app/)

[GitHub](https://github.com/DenKuznets)

---

## About me

I've been doing web development since 2022. I never stop learning new technologies and keeping up with the latest front-end innovations. My knowledge of English allows me to receive information first-hand without waiting for translation. I have some experience in commercial development. I worked part-time in a web studio collaborating with a backend programmer and web designer and now know how to meet a deadline while keeping all the important parts of a site pixel perfect to Figma design.

---

## Skills

```REACT```  ```NEXTJS``` ```TAILWIND``` ```TS``` ```MUI``` ```REDUX``` ```REST``` ```UNIT TESTING``` ```STORYBOOK``` ```STYLED-COMPONENTS``` ```HTML CSS JS```

<sup>(for every listed skill here i have at least one project demo in my portfolio)</sup>

---

## Code example

Codewars | ```7 kyu``` | Determine if the poker hand is flush

<sub>Determine if the poker hand is flush, meaning if the five cards are of the same suit.
Your function will be passed a list/array of 5 strings, each representing a poker card in the format "5H" (5 of hearts), meaning the value of the card followed by the initial of its suit (Hearts, Spades, Diamonds or Clubs). No jokers included.
Your function should return true if the hand is a flush, false otherwise.
The possible card values are 2, 3, 4, 5, 6, 7, 8, 9, 10, J, Q, K, A</sub>

```
function isFlush(cards) {  

  for(let i = 0; i < cards.length - 1; i++){
    if(cards[i][cards[i].length - 1] !== cards[i + 1][cards[i + 1].length - 1]) return false;
  }

  return true ;
}
```