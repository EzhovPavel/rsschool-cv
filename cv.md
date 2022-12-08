## [rsschool-cv](https://github.com/EzhovPavel)

** 

# Yazhou Pavel

** 

## Contacts

* Location: Gomel, Belarus;
* Phone: +375 29 867-11-53;
* Email: fadion@bk.ru;
* GitHub: EzhovPavel.

** 

## About Me

I work in the SEO team. I am looking for a new way to gain knowledge, experience and earnings. For this purpose, I learned HTML, CSS & JS to try something new.

** 

## Skills

* HTML
* CSS/SASS;
* JavaScript;
* Figma
* jQuery
* Bootstrap
* Git

** 

## Code Example

function hideTabContent() {
    
    tabsContent.forEach(item => {
        item.classList.add('hide');
        item.classList.remove('show', 'fade');
    });

    tabs.forEach(item => {
        item.classList.remove('tabheader__item_active');
    });
}

function showTabContent(i = 0) {
    tabsContent[i].classList.add('show', 'fade');
    tabsContent[i].classList.remove('hide');
    tabs[i].classList.add('tabheader__item_active');
}

hideTabContent();
showTabContent();

tabsParent.addEventListener('click', function(event) {
    const target = event.target;
    if(target && target.classList.contains('tabheader__item')) {
        tabs.forEach((item, i) => {
            if (target == item) {
                hideTabContent();
                showTabContent(i);
            }
        });
    }
});


** 
## Experience

Education
University: FRANCISK SKORINA GOMEL STATE UNIVERSITY;
Courses:
IT ACADEMY: HTML, CSS & JS, ADVANCED JS.

* 

## English
A2