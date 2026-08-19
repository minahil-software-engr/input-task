1. Task ka Purpose:
Is task ka main purpose input field se user ki value lena hai.
User input field mein koi bhi text enter karega.
User button par click karega.
Button click hone par input ki current value ek alert box mein show hogi.
Is task mein input ki value read karne ke liye .value property use karni hai.

2. HTML Structure:
Sabse pehle HTML document create kiya gaya hai.
DOCTYPE browser ko batata hai ke document HTML5 mein hai.<html> poore webpage ka root element hai.<head> mein webpage ki basic information rakhi gayi hai.charset="UTF-8" characters ko properly display karne ke liye use hota hai.<title> browser ke tab ka naam set karta hai.<body> mein webpage ke visible elements rakhe jate hain.
  
3. Heading:
Webpage par ek heading rakhi gayi hai.
Heading user ko batati hai ke webpage ka purpose input value ko different methods se check karna hai.
Isse user ko samajh aata hai ke neeche input field aur button kis liye hain.

5. Input Field:
Ek text input field create ki gayi hai.
Is field mein user apni desired value type kar sakta hai.
Input ko ek unique ID di gayi hai.
JavaScript isi ID ki help se input field ko find karegi.
placeholder user ko hint deta hai ke input field mein kuch type karna hai.
Input field mein jo value user type karta hai, woh uski current value hoti hai.

7. Button:
Input ke saath ek button create kiya gaya hai.
Button ko bhi ek unique ID di gayi hai.
JavaScript isi ID se button ko access karegi.
User jab button par click karega to JavaScript ka click event execute hoga.

9. JavaScript mein Input ko Select Karna:
JavaScript mein document current webpage ko represent karta hai.
getElementById() method HTML element ko uski ID ke through find karta hai.
Input ki ID use karke input field ko JavaScript mein access kiya gaya hai.
Input field ko ek variable mein store kiya gaya hai.
Ab variable ke through input ki properties access ki ja sakti hain.

11. JavaScript mein Button ko Select Karna:
Button ko bhi getElementById() ke through find kiya gaya hai.
Button ko ek variable mein store kiya gaya hai.
Ab JavaScript is button par events apply kar sakti hai.

13. Click Handler:
Button par click event listener lagaya gaya hai.
addEventListener() kisi specific event ko listen karta hai.
Yahan event click hai.
Jab user button par click karta hai, to associated function execute hota hai.
Is function ko click handler kehte hain.
Click handler ke andar woh saara logic hota hai jo button click hone ke baad perform karna hai.

14. .value — First Method:
.value input field ki current value read karne ke liye use hota hai.
Agar user input mein Hello type kare, to .value ka result Hello hoga.
Agar user input change kare, to .value bhi new/current value return karega.
Input elements ke liye .value sabse appropriate method hai.
Isi wajah se task ki requirement mein specifically .value use karne ko kaha gaya hai.
Example Concept:
User ne Pakistan type kiya.
.value → Pakistan

16. textContent — Second Method:
textContent kisi HTML element ke text content ko read karne ke liye use hota hai.
Normal elements jaise paragraph, heading ya div ke text ke liye yeh useful hai.
Input element mein user ki typed value normal text content ke taur par store nahi hoti.
Isliye input ki current typed value lene ke liye textContent appropriate nahi hai.
Input ke case mein usually iska result empty string hota hai.
Comparison:
.value → input ki current value 
.textContent → input ki typed value nahi deta 

18. innerHTML — Third Method
innerHTML kisi element ke andar maujood HTML content ko read karta hai.
Agar kisi div ke andar HTML elements hon, to innerHTML unka HTML content return kar sakta hai.
Lekin <input> ke andar user ki typed value HTML content nahi hoti.
Isliye input ki current value read karne ke liye innerHTML use nahi hota.
Input ke case mein iska result normally empty hota hai.
Comparison:
.value → input ki current value 
.textContent → typed value nahi deta 
.innerHTML → typed value nahi deta

20. Alert:
alert() browser mein ek popup message show karta hai.
Input ki .value ko alert ke andar display kiya jata hai.
String aur input value ko + operator ke through combine kiya ja sakta hai.
\n ka use new line ke liye hota hai.
Isliye teen results alert mein separate lines par show hote hain.
First line → .value ka result
Second line → .textContent ka result
Third line → .innerHTML ka result

22. The Challenge — Input Clear Karna
Challenge mein ek additional requirement di gayi hai.
Alert show hone ke baad input field ko clear karna hai.
Pehle input ki current value read ki jati hai.
Us value ko alert mein show kiya jata hai.
Alert close hone ke baad input ki value ko empty kar diya jata hai.
Empty string ka matlab hai input field ke andar koi text nahi rahega.
