# NFL-Website
NFL Registration Page (Javascript code)

<script>
            function RegistrationForm(firstName, lastName, passWord, regDate, favTeam, phonenum, email, infour1) {
                this.firstName = firstName;
                this.lastName = lastName;
                this.passWord= passWord;
                this.regDate = regDate;
                this.favTeam = favTeam;
                this.phonenum = phonenum;
                this.email = email;
                this.infour1 = infour1;
                this.PrintForm = PrintForm;
            }
            function PrintForm(){
                document.write(this.firstName + this.lastName + "<p> has registered to receive updates on the NFL \n\
                                                                and their favorite team," + this.favTeam + ", via Text and Email.</p>");
                document.write("<p> Date of registration: " + this.regDate + "</p>");
                document.write("<p> You will be contacted via Text @" + this.phonenum);
                document.write("You will be contacted via Email @" + this.email + "</p>");
                document.write("<p> Additional Comments made to Website: " + this.infour1 + "</a> </p>");
            }
            function Validate() {
                with (document.registerForm){
                    
                    reg = new RegistrationForm (firstName.value, lastName.value, passWord.value, regDate.value, favTeam.value, phonenum.value, email.value, infour1.value);                }
                      
                with (reg) 
                {
                 reg.PrintForm();   
                }
                return true;
            }
        </script>
        
  //Following script code is for the popup alerts to show examples of how to fill out form//
  
        <script>
            function changeColor()
            {
               document.body.style.background="red" ;
            }
            function myName()
            {
                alert("Enter First Name as Such: MARK");
            }
            function myLast()
            {
                alert("Enter Last Name as Such: EULALIA");
            }
            function myPass()
            {
                alert("Password must be a combination of at LEAST 8 numbers/letters!");
            }
            function myDate()
            {
                alert("Enter Date as Such: 12/23/2013");
            }
            function myFav()
            {
                alert("Enter City Name and Team Name!");
            }
            function myNum()
            {
                alert("Only enter Numbers such as: 3146577889");
            }
            function myEmail()
            {
                alert("Example: hellpworld@domainname.com");
            }
            function secondImg(x)
            {
                x.src="formex.jpg";
            }
            function firstImg(x)
            {
                x.src="question.png";
            }
        </script>
