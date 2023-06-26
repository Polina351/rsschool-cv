# Deniskina Polina
## Contacts
* **Location:** Saint Petersburg, Russia
* **Phone:** +7 963 341 45 58
* **Email:** polinaoioi67@gmail.com
* **GitHub:** [Polina351](https://github.com/Polina351)
## About me
I am sociable, responsible and I like to learn new things. My hobbies are outdoor activities, reading books and programming.
## Skills
* HTML
* CSS
* JavaScript (base)
* Git (base)
## Code Example
```javascript
let inputs = document.querySelectorAll('input')
let button = document.querySelector('#btn')

button.addEventListener('click',function() {
	for (let input of inputs) {
		if (input.value === input.dataset) {
			input.classList.add('right')
		} else {
			input.classList.add('wrong')
		}
	}
});
```