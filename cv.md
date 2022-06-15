# Yan Bocharov
---
## Contacts
---
* **Location** : Tula
* **Phone** : 8 (960) 615-82-82
* **Email** : yan.bocharovv@gmail.com
* **GitHub** : https://github.com/YanBocharov

## Skills
---
* ***HTML***
* ***CSS (SCSS / SASS)***
* ***JS (Basic)***
* ***GIT***
* ***FIGMA***

## About Me
---

I really love programming and communication with people. I will be useful in different areas, as I like to learn something new. And I also have cookies!

---

## Code Example 
---
```
let tab = document.querySelectorAll('.price__block-content'),
        info = document.querySelector('.price__wrapper1'),
        tabContent = document.querySelectorAll('.price__wrapper2');

    function hideTabContent(a) {
        for(let i = a; i < tabContent.length; i++) {
            tabContent[i].classList.remove('show');
            tabContent[i].classList.add('hide');
        }
    }
    hideTabContent(1);

    function showTabContent (b) {
        if (tabContent[b].classList.contains('hide')) {
            tabContent[b].classList.remove('hide');
            tabContent[b].classList.add('show');
        }
    }
    info.addEventListener('click', function (event) {
        let target = event.target;
        event.preventDefault();
        if (target && target.classList.contains('price__block-content')) {
            for (let i = 0; i < tab.length; i++) {
                if (target == tab[i]) {
                    hideTabContent(0);
                    showTabContent(i);
                    break;
                }
            }
        }
    });
```
## My favorite quote 
 
> *Anyone who has never made a mistake has never tried anything new.* - ***Albert Einstein***


## Education
* ***University*** : Tula State University, Customs
* ***Curses***
    + [HTML Academy](https://htmlacademy.ru/study 'HTML Academy')
    + : [Udemy](https://www.udemy.com/ 'Udemy')
    + : [BeOnMax Curses](https://beonmax.com/ 'BeOnMax')

## English
---
### A2/B1 (Pre-Intermediate) 
I am currently learning English



