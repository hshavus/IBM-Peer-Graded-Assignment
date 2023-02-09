<center>
    <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0105EN-SkillsNetwork/labs/Module2/images/SN_web_lightmode.png" width="300" alt="cognitiveclass.ai logo">
</center>

<h1>My Jupyter Notebook on IBM Watson Studio</h1>

__Sinan__<br>
Data Analyst

_I am interested in data science because I want to become a data scientist in finance industry and I believe data science is a field that offers a high degree of job satisfaction as I will be solving complex problems and making a real impact on businesses and society._

<h3>Code below draws a heart using a for loop</h3>


```python
for row in range(6):  
    for col in range(7):  
        if (row==0 and col %3 !=0) or(row==1 and col %3==0) or(row-col==2) or(row+col==8):  
            print("*",end=" ")  
        else:  
            print(end=" ")  
    print() 
```

     * *  * *  
    *   *   * 
    *      * 
     *    *  
      *  *   
       *    


<hr>
<ul>
    <li>ONE</li>
    <li>TWO</li>
    <li>THREE</li>
    <li>FOUR</li>
    <li>FIVE</li>
</ul>
<hr>
<ol>
    <li>Monday</li>
    <li>Tuesday</li>
    <li>Wednesday</li>
    <li>Thursday</li>
    <li>Friday</li>
</ol>
<hr>
<table>
  <tr>
    <td>Name</td>
    <td>Email</td>
    <td>Address</td>
  </tr>
</table>
<hr>
<a href="https://www.ibm.com/us-en/">IBM</a>
