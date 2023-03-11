# Curriculum Vitae
### Basic Information
- *Name*:  Alexandr Sazonnikov
- *Nationality*: Russian
- *City*: Samara
- *Date Of Birth*: 30<sup>th</sup> July, 2003

### Contacts
- *Email*: sanek15056@gmail.com
- *Discord Username*: Quaqva

### About Me
  &ensp;I am a beginner in IT delevopment. I love conquering new heights and try to gain as much knowledge as possible! My favourite programming language is *C#*.
### Hard Skills
- HTML/CSS/JS
- C# (.NET Framework, ASP .NET Core, Entity Framework)
- Python (numpy, sklearn, pandas)
- Java (Android development)
### Code example

  Here is Roman Numeral Converter that i wrote on JS:
  <pre><code>
  function convertToRoman(num) {
    if (num <= 0) return '';

    let romans = {1000: 'M', 900: 'CM', 500: 'D', 400: 'CD',
    100: 'C', 90: 'XC', 50: 'L', 40: 'XL', 10: 'X', 9: 'IX', 5: 'V', 4: 'IV', 1: 'I'};

    let convertibles = Object.keys(romans).map(num => parseInt(num)).sort((a, b) => b - a), 
        digitInd = 0;

    while (convertibles[digitInd] > num)
      digitInd++;

    let digit = convertibles[digitInd];
    return romans[digit] + convertToRoman(num - digit);
  }
  </code></pre>
### Job Experience
  &ensp;As of now, I do not have any job experience in IT, but looking forward to gain some!
### Education
  - Right now i study at the **Samara University**. I am getting a speciality called *"Fundamental informatics and information technologies"* from 2021.
  - I also did courses on [freecodecamp.org](https://www.freecodecamp.org/Quaqva) where i learnt HTML, CSS and JS basics this year. It is a very nice website with good material presentation.
  - I decided to improve my knowledge further and signed up for *Frontend course* in **the Rolling Scopes School**.
### English
  &ensp;Intermediate (B2)
