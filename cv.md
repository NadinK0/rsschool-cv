# Nadezhda Klinskaya


## Contacts
* **Phone:** +79045531416
* **Telegram:** @N_a_d_i_n_a
* **GitHub:** NadinK0
* **e-mail:** npantelyeva@gmail.com


## About me
While on maternity leave, I decided to try something new. My choice was web-programming. I started studying recently, but I really like to get new knowledge. I try to achieve my goals, so I believe that I can master this profession.

## Skills
* HTML
* CSS
* JS
* Adobe Photoshop
* SQL

## Education
* **Saint Petersburg Electrotechnical University «LETI»**
    + Faculty of Computer Technologies and Informatics
* **Tomsk State University**
    + Course "Web programmer: from scratch to the first projects"


## Code example
**Instruction from codewars** *Complete the solution so that it splits the string into pairs of two characters. If the string contains an odd number of characters then it should replace the missing second character of the final pair with an underscore ('_').*
```
function solution(str){
    let current_arr = str.split('');
    let pair_arr= [];
    if (current_arr.length % 2 === 0)
    {
        for (let i = 0; i < current_arr.length; i += 2) 
        {    
            pair_arr.push(current_arr[i]+current_arr[i+1])
        } 
        return(pair_arr);
    }    
    else 
    {
        for (let i = 0; i < current_arr.length - 1; i += 2)
        {
            pair_arr.push(current_arr[i]+current_arr[i+1])
        }
        pair_arr.push(current_arr[current_arr.length-1]+"_")
        return(pair_arr);
    }
}
```
## Languages
* Russian (Native)
* English (Intermediate)

