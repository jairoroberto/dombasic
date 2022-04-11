# Básico DOM com Tailwind
**https://tailwindcss.com/**
_____________________
- [x] Tailwind - __Utility First CSS__
- [x] __getElementsByTagName__
- [x] __getElementById__
- [x] __getElementsByClassName__
- [x] __querySelector__
- [ ] __querySelectorAll__
- 


###Javascript DOM - Example:
```
//const btnCTA = document.querySelector('button');
//const btnCTA = document.querySelector('.btn-cta');
//const btnCTA = document.querySelector('#btnCTA');
// TAG, #ID, .CLASS, [ATRIBUTO] - querySelector

//const btnCTA = document.getElementById('btnCTA');
//const btnCTA = document.getElementsByClassName('btn-cta');

//console.log(btnCTA);

const result = document.querySelector('#result');
const inputForm = document.querySelector('form');

btnCTA.addEventListener('click', function (e) {
    e.preventDefault();
    result.innerHTML = '<h3>Digite um texto válido</h3>';
    result.classList.add('border-2','border-rose-600', 'bg-yellow-200');

});
```


