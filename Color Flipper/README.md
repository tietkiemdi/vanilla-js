su kien click

btn.addEventListener('click', function(){

    const randomNumber = getRandomNumber();
    console.log(randomNumber);

    document.body.style.backgroundColor = colors[randomNumber];

    color.textContent = colors[randomNumber];  


});




