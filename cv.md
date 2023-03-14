## Sinitsa Kiryl
E-mail: kns.inbox@gmail.com
Skype: kirill.sinitsa

### Education
* 2015 – 2020 Institute of Informational Technologies BSUIR, Department of microprocessor systems and networks
* 2004 – 2005 Belarusian National Technical University, Department of International Economic Relations, Magistracy
* 1999 – 2004 Belarusian National Technical University, Department of International Economic Relations

### Additional education
Courses in Streamline Language School , Advanced+ (C1+).
Online courses «Job of Frontend-developer» on education platform Skillbox (HTML5, CSS3, JavaScript)

### Work Experience
Since 01.08.2017 to 30.04.2022 – Minsk Motor Plant, software engineer
From 07.09.2010 to 31.07.2017 – Minsk Motor Plant, engineer for the organization and regulation of labor.

### Projects
I took part in translation of several books for publishing house «Piter», including:
*	Bart Baesens «Beginning Java Programming: The Object-Oriented Approach»
*	Allen B. Downey «Think Data Structures. Algorithms and Information Retrieval in Java»
*	Cathy O’Neil, Rachel Schutt «Doing Data Science».

### Professional skills
1.	C# – thesis "Software tool for piece work accounting" (MVC, WPF, EntityFramework, Prism, AutoMapper, NLog). Please, find at Github: https://github.com/kirillsinitsa/rates-fixer
2.	FoxPro and Visual FoxPro – applications for file databases
3.	MS Excel – programmatically created reports

### Code example
```
function bubbleSort(arr) {
  let count = 0;
  let needIteration = true;
  while (needIteration) {
    needIteration = false;
 
    for (let i = 0; i < arr.length; i++) {
      for (let j = 0; j < arr.length - i - 1; j++) {
        if (arr[j] > arr[j + 1]) {
          const temp = arr[j + 1];
          arr[j + 1] = arr[j];
          arr[j] = temp;
          count += 1;
          needIteration = true;
        }
      }
    }
    return count;
  }
}
```