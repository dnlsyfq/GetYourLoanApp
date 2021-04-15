# GetYourLoanApp

### Template / String literal 

```
    var summaryText = "Dear " + la.ApplicantName + ", " + reviewText + " Your risk profile is " + riskProfile;


    var summaryText = `Dear ${la.ApplicantName}, 
    your application for ${"$" + la.LoanAmount}, ${reviewText}.  
    Your risk profile is ${riskProfile}`;
    return summaryText;
```