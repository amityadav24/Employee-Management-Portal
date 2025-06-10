It's is simple employee management portal created with the help of html and javascript.
    //if want to store data locally add this below comment. 
    let prevdata = [];
    prevdata = JSON.parse(localStorage.getItem("employee"))

    prevdata.push(employeeData);
    localStorage.setItem("employee", JSON.stringify(prevdata));