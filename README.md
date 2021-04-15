# GetYourLoanApp

### Template / String literal 

```
    var summaryText = "Dear " + la.ApplicantName + ", " + reviewText + " Your risk profile is " + riskProfile;


    var summaryText = `Dear ${la.ApplicantName}, 
    your application for ${"$" + la.LoanAmount}, ${reviewText}.  
    Your risk profile is ${riskProfile}`;
    return summaryText;
```

### Destructure Arrays 

```
        var isEmployed = la.Factors[0];
        var hasKids = la.Factors[1];
        var hasLoans = la.Factors[2];
        var hasCreditcards = la.Factors[3];
        
        var [isEmployed, hasKids, hasLoans, hasCreditCards] = la.Factors;
```

### Destructure Objects

```
var {Id:a, Name:b} = object;
```

### String

* .trim()
* .toLowerCase()
* .startsWith()
* .endsWith()
* .includes()

### Integer

* Number.isInteger(value)
