
﻿<%@ Page Language="C#" AutoEventWireup="true" CodeBehind="Home.aspx.cs" Inherits="Data_Entery_to.Home" %>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
    <title></title>
    <link rel="stylesheet" href="~/StyleSheet.css"/>
</head>
<body>
    <div class="wrapper">
        <section class="contact section">
            <h1 class="section-title">
                DIRE DAWA ADMINSTRATION TRANSPORT & LOGISTICS AUTHORITY 
            </h1>
            <br /><br /><br /><br />
            <div class="contact-page container grid">
                <form action="" class="contact-form grid" id="contact-form">
                    <div class="contact-subtitle grid">
                        <div class="contact-subtitle">
                            <p1>
                                Wel Come To DLRS <br />
                                To login, enter your correct User Name and <br /> Password then click on Log In.<br />
                            </p1>
                            <br />
                        </div>
                    </div>
                    <div class="contact-group grid">

                        <div class="contact-card">
                            <label for="name" class="contact-label">User Name</label>
                             <input type="text" name="Usert_Name" id="User Name" required
                              placeholder="Enter your Usert Name here!" class="contact-input">
                        </div>


                        <div class="contact-card">
                            <label for="name" class="contact-label">Password</label>
                            <input type="password" name="Password" id="Password" required
                                   placeholder="Enter your Password here!" class="contact-input"> 

                        </div>

                    </div>
                        
                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" asp-for="IsBlogActive">
                            <label class="form-check-lable" asp-for="IsBlogActive">Show my password</label>
                        </div>
                        <button type="submit" class="contact-send button">LOG IN</button>

                </form>
                <div class="social-icon">
                    <a href="#" target="_blank"><i class='bx bx1-linkedin'></i></a>
                    <a href="#" target="_blank"><i class='bx bx1-behance'></i></a>
                    <a href="#" target="_blank"><i class='bx bx1-github'></i></a>
                    <a href="#" target="_blank"><i class='bx bx1-dribbble'></i></a>
                </div>

            </div>
        </section>

        <section>

            <div class="contact-subtitle grid">
              <div class="contact-subtitleee">
               <p1>
                  Wel Come To Activation! <br />
                  To activate your user registration form, <br /> enter your correct Activation Code and <br /> then click on ACTIVATE.<br />
               </p1><br />
              <div class="contact-card">
                <label for="name" class="contact-labelll">Activation Code</label>
                <input type="text" name="Activation Code" id="Activation Code" required
                 placeholder="Enter your activation code here!"class="contact-inputtt">
                 </div><br/>
              <div class="form-checkkk">
              <input class="form-check-input" type="checkbox" asp-for="IsBlogActive">
              <label class="form-check-lable" asp-for="IsBlogActive">Show my password</label> 
              </div><br/>
              <button type="submit" class="contact-send buttonnn">ACTIVATE</button><br /><br />
              <p1>
                Wel Come To USER REGISTRATION <br />
                To create new user, enter your correct info and <br /> then click on REGISTER.<br />
              </p1><br />

              </div>
             </div><br />

            <div class="contact-card">
              <label for="name" class="contact-labell">User Id</label>
              <input type="text" name="User_Id" id="User Id" required
               placeholder="Your User Id will auto. Entered!" class="contact-inputt">
           </div>
           <div class="contact-card">
              <label for="name" class="contact-labell">First Name</label>
              <input type="text" name="Usert_Name" id="First Name" required
               placeholder="Enter your First Name here!" class="contact-inputt">
           </div>
           <div class="contact-card">
              <label for="name" class="contact-labell">Middle Name</label>
              <input type="text" name="Middle_Name" id="Middle Name" required
               placeholder="Enter your Middle Name here!" class="contact-inputt">
           </div>
           <div class="contact-card">
              <label for="name" class="contact-labell">Last Name</label>
              <input type="text" name="Last_Name" id="User Name" required
               placeholder="Enter your Last Name here!" class="contact-inputt">
           </div>
           <div class="contact-card">
            <label for="name" class="contact-labell">User Name</label>
            <input type="text" name="Usert_Name" id="User Name" required
            placeholder="Enter your Usert Name here!" class="contact-inputt">
          </div>
          <div class="contact-card">
            <label for="name" class="contact-labell">Password</label>
            <input type="password" name="Password" id="Password" required
             placeholder="Enter your Password here!" class="contact-inputt"> 
          </div><br/>
          
            <div class="form-checkk">
               <input class="form-check-input" type="checkbox" asp-for="IsBlogActive">
               <label class="form-check-lable" asp-for="IsBlogActive">Show my password</label> 
            </div><br/>

          <div class="contact-card">
            <label for="name" class="contact-labell">Password Ensured</label>
            <input type="password" name="Password" id="Password Ensured" required
              class="contact-inputt"> 
          </div>
          <div class="contact-card">
           <label for="name" class="contact-labell">Date Registered</label>
           <input type="date" name="Usert_Name" id="Date Registered" required
            class="contact-inputt">
           </div>
          <div class="contact-card">
             <label for="name" class="contact-labell">Role</label>
             <input type="text" name="Role" id="Role" required
              class="contact-inputt">
          </div>
            <button type="submit" class="contact-send buttonn">REGISTER</button><br />

          
        </section>

    </div>

</body>
</html>
