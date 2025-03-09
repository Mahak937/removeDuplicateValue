 x = [1,2,4,2,5]
        console.log(x.filter((item, index) => x.indexOf(item) !== index)); //2    "removed duplicate value"
        console.log(x.filter((item, index) => x.indexOf(item) === index));  //1,2,4,5         "remaining duplicate value || find duplicate value 
        console.log([...new Set(x)]);   
