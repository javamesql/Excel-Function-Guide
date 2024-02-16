<h1>Excel Function Guide</h1> 

<h2>To demonstrate my proficiency in Excel functions, I will be going through the process of using the functions.</h2>

<h2>XLOOKUP</h2>

![image](https://github.com/javamesql/Excel-Function-Guide/assets/141413672/f23ee90f-f359-4632-b656-07e0c19c29a7)

XLOOKUP consists of 3 required inputs, the lookup value, lookup array, and return array. The rest that are in brackets ([]) are optional. It is used to find the return value of the first match that corresponds to your lookup value.

![image](https://github.com/javamesql/Excel-Function-Guide/assets/141413672/db42995f-6eb3-45ce-849a-f3d9e78d5ad9)

You will need a starting value to look up, in this case it's Stark Industries. We will be looking for the profit. We start by selecting Stark Industries as the lookup value (blue), then select the array that we will be searching for the value in (red), and finally we select the array that we will be searching for the profit in (purple).

![image](https://github.com/javamesql/Excel-Function-Guide/assets/141413672/5b473c81-8084-4d48-b51f-7459b9acdcb1)

Add another lookup value and drag the function cell down to easily fill in the new profit value.

<h2>VLOOKUP</h2>

![image](https://github.com/javamesql/Excel-Function-Guide/assets/141413672/afad2131-65c4-4af3-89f6-1e4d5f1eb8bf)

VLOOKUP consists of a starting value to look up, which is Monty and Loop Media. We will be looking for revenue. We will be selecting the lookup value (Monty or Loop Media), the table we will be drawing our answer from, and the vertial column our answer is in (column 4). The V in VLOOKUP comes from the significance of vertical columns when using the function. 

<h2>SUMIF</h2>

![image](https://github.com/javamesql/Excel-Function-Guide/assets/141413672/76876e07-c5bf-4516-ae32-aa014d7ec2ee)

The SUMIF function consists of the range where we will look up our our range (Technology), criteria (Category/Red), and our sum range where our answer will be located (Profit). SUMIF is a function that calculates the sum within a given range when given the criteria and conditions.

<h2>SUMIFS</h2>

![image](https://github.com/javamesql/Excel-Function-Guide/assets/141413672/2ead1a49-a33e-4c6c-a92e-6f76c681b9db)

SUMIFS' use is similar to SUMIF but with more than one criteria. SUMIF's criteria was Category, this SUMIFS' function's criteria are Category and Status. SUMIFS consists of the sum range (range of what we are looking for), the first criteria range (Category), the first criteria (Service or Technology in the example), the second criteria range (Status), and the second criteria which is ON. This results in the sum of profit from businesses that have the category of service or technology and businesses that have the status of ON.

<h2>COUNTIF</h2>

![image](https://github.com/javamesql/Excel-Function-Guide/assets/141413672/9eacac44-62d8-4df8-8ace-ee4f852f9b25)

COUNTIF is straightfoward in which you choose the range where you want to count and what you want to count. In this example, the range is the Status and the criteria is ON. This means that there are 7 businesses active from the table.
