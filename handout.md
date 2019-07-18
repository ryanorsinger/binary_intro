### Intro to Binary Numbers - Why should you care?

> "Binary"
>
> *adjective*
>
> 1. relating to, composed of, or involving two things.
> 2. relating to, using, or expressed in a system of numerical notation that has 2 rather than 10 as a base.
>
> *noun*
>
> 1. the binary system: binary notation.
> 2. something having two parts.

### Binary is about more than counting with zeros and ones

- A way to represent letters, characters, and symbols (English, Spanish, Chinese, etc..) to computers. To a computer, there's no such thing as the number 23 or the letter "A". Those are representations meaningful to people, but they are actually a binary number on a lookup table that points to a picture of the letter "A" or the number 23. 
- In addition to letters and numbers, computer designers represented command characters like `Enter`, `Backspace`, `Shift`, or `Interrupt` as binary so they could exist on the lookup table and map to keyboard keys. Each key needs to point to a binary number on that lookup table.
- Bitwise operators = faster/cheaper than division and multiplication for low energy processors
- Binary logic AKA Boolean logic gives us boolean algebra. Boolean logic is a "BIG DEAL"
- Bitmasking, which is used in everything from `audio compression` to video game graphics

### Why is binary a big deal for computers and software development?

- In a way, software development is all about representing patterns in order to represent information.

- People have created all kinds of counting systems. Base 2, Base 10, Base 8, Base 16.

- Computers and Base 2 work because a 0 represents off and a 1 represents on

- Think of each binary exponent as a switch that can be turned on or off.

- The first computers were physical computation machines. A clock is a physical computer!

  The Ancient Greeks invented a machine called the `Antikytera` that computed months and seasons

  <img src="/Users/moon/binary_intro/hublot-antikythera-1.jpg" height=250>

- The second wave of computers were electrically powered, but analog. What does that mean?

  - When you think `analog`, think record players. They're electrically powered but not digital.
  - This was when we used vacuum tubes and transistors. Computers were the size of entire rooms.

- Digital computers store the `on` or `off` of a switch as a `0` or a `1`. With digital representation of bits, we can store massive amounts of information on modern computers. A keyless remote for a vehicle these days has the same computing power and storage as the Apollo 11 Guidance Computer that got 

- Allows the expression of as many letters, numbers, symbols, and command codes in a `byte` as possible. A `byte` is 8 bits. For example, the ASCII has 256 characters, numbers, symbols, and control codes. 

#### You can count to 1,023 on your fingers!

<img src="/Users/moon/binary_intro/binary_on_fingers.png" height=300">

##### Each finger represents an exponent of 2 from 0 to 9

<img src="/Users/moon/binary_intro/binary_on_one_hand.gif" height="275">

<table>

​    <tr>
        <th>Expression</th>
        <th>Exponent</th>
        <th>Value in Base 10</th>
    <tr>
    <tr>
        <td>2<sup>0</sup></td>
        <td>0</td>
        <td>1</td>
    </tr>
    <tr>
        <td>2<sup>1</sup></td>
        <td>1</td>
        <td>2</td>
    </tr>
    <tr>
        <td>2<sup>2</sup></td>
        <td>2</td>
        <td>4</td>
    </tr>
    <tr>
        <td>2<sup>3</sup></td>
        <td>3</td>
        <td>8</td>
    </tr>
    <tr>
        <td>2<sup>4</sup></td>
        <td>4</td>
        <td>16</td>
    </tr>
    <tr>
        <td>2<sup>5</sup></td>
        <td>5</td>
        <td>32</td>
    </tr>
    <tr>
        <td>2<sup>6</sup></td>
        <td>6</td>
        <td>64</td>
    </tr>
    <tr>
        <td>2<sup>7</sup></td>
        <td>7</td>
        <td>128</td>
    </tr>
    <tr>
        <td>2<sup>8</sup></td>
        <td>8</td>
        <td>256</td>
    </tr>
    <tr>
        <td>2<sup>9</sup></td>
        <td>9</td>
        <td>512</td>
    </tr>
</table>

#### More info

- ASCII lookup table `https://www.ascii-code.com/`
- Bitmasking and video game graphics `https://gamedevelopment.tutsplus.com/tutorials/how-to-use-tile-bitmasking-to-auto-tile-your-level-layouts--cms-25673`
- "Why Use Binary" by Professor Brailsford `https://www.youtube.com/watch?v=thrx3SBEpL8`