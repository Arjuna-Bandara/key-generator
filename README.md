# key-generator
html and js tool to generate passwords. 

#function for generating random passwords


    function makeid() {
        var text = "";

        //ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789
        
        var possible = "ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789";

        //change limit of i to change the length of the key
        for (var i = 0; i < 8; i++)
            text += possible.charAt(Math.floor(Math.random() * possible.length));

            console.log(text);
        ;

        document.getElementById("show").value = text;
            

        return text;
    }

#change 'possible' variable's value to 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789' for include simple letters in generated passwords.


#live preview is available on
https://arjunauop.github.io/key-generator/password-generator.html

