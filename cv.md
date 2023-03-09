# Ilya Makeenko
# My contact info
* **Phone:** +375 29 654-37-05
* **E-mail:** makeenko.005@gmail.com
* **Git-hub:** github.com/jetie000
# About me
  I'm 18 years old BSUIR student. My goal is to not stay at the same place and keep moving forward. I think that RS courses will help me to find myself in IT sphere. Also I have good soft skills, that can help to achieve my goals.
# Skills
* HTML
* CSS
* C/C++
* JS
* Git/Github
* Photoshop
# Code example
**(password input from my course project)**
```
cout << "Введите пароль: ";
	do {
		bufPassword[i] = _getch();	
		if (bufPassword[i] == '\r')
			break;
		i++;
		if (bufPassword[i - 1] == 8 && i - 1 > 0)
		{
			cout << (char)8 << ' ' << (char)8;
			i--;
			i--;
			continue;
		}
		if (bufPassword[i - 1] == 8 && i - 1 == 0)
		{
			i--;
			continue;
		}
		putchar('*');
	} while (i < 30);
	bufPassword[i] = '\0';
  ```
# Education
BSUIR, Faculty of information technologies and control (second year)
# Languages
* Russian - native
* English - B1
