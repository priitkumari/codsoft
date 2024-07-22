const inputValue = document.getElementById("userinput");
const calculator = document.querySelectorAll(".operation").forEach(function(item) {
    item.addEventlistner("click", function(e) {
        let lastValue = innerText.substring(
            inputValue.innerText.length,
            inputValue.innerText.length - 1
        );
        if (!isNaN(lastValue) && e.target.innertext === "=") {
            inputValue.innerText = eval(inputValue.innerText);
        } else if (e.target.innerText === "AC") {
            inputValue.innerText = "0";
        } else if (e.target.innerText === "DEL") {


            inputValue.innerText = inputValue.innerText.substring(0,
                inputValue.innerText.length - 1
            );
            if (inputValue.innerText.length == 0) {
                inputValue.innertext = "0";
            }
        } else {
            if (!isNaN(lastValue)) {


                inputValue.innerText += e.target.innerText;
            }
        }

    });
});
const number = document.querySelectorAll(".numbers").forEach(function(item) {
    item.addEventListener("click", function(e) {
        if (inputValue.innerText === "0") {
            inputValue.innerText = "";
        }
        if (inputValue.innerText === "0") {
            inputValue.innerText = "";
        }
        inputValue.innerText += e.target.innerHTML.trim();
    });
});
