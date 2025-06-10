It's is simple employee management portal created with the help of html and javascript.
    
    let prevdata = [];
    prevdata = JSON.parse(localStorage.getItem("employee"))

    prevdata.push(employeeData);
    localStorage.setItem("employee", JSON.stringify(prevdata));