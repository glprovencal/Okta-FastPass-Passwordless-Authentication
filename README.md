# Okta-FastPass-Passwordless-Authentication

</p>
<p>
<h2> </h2>
  Hi,<p>
    
  Here is another hands-on IAM lab in Okta where i configured a passwordless authentication using Okta FastPass. This includes Authentication and Global Session policies and rules. 
<p>Passwords are the weakest link in workforce authentication. They are phished, reused, and expensive to reset.
  
The goal is to move a pilot user to phishing-resistant, passwordless sign-in using Okta Verify (FastPass)
<h2> </h2>
<p>
Phase 1:   <p>
  Demo group created and a pilot user(Ashley Bikes) assigned to the group.
  <p>
        Global policy created and assigned to the Demo group  <p>


<h2> </h2>
<img width="764" height="393" alt="demo group+user" src="https://github.com/user-attachments/assets/03302850-ae1a-4da8-8eb7-de685c666848" />
<h2> </h2>
      </p>     <p> 
Phase 3: Authenticators  <p>
     <p>    
 In Security > Authenticators:<p>  
  Authenticator enrollment policy (Security > Authenticators > Enrollment tab)<p>  
    Establish the session with any authenticator allowed by the app policy, not password-only.
 <p>
    Global Session Policy created and assigned to the Demo group <p>
    Created authentication policy with a one factor type (Okta Verify - FastPass).<p>   
    Assigned Okta dashboard application to the authentication policy  <p>    
1.       
<img width="736" height="412" alt="global policy=demo grppng" src="https://github.com/user-attachments/assets/e85a69fa-5a7c-4b4c-be06-313c265a9d97" />
<img width="811" height="411" alt="Demo Policy" src="https://github.com/user-attachments/assets/97b4c04d-2ba5-4a50-ba03-66f0ff12a8c3" />
<img width="627" height="310" alt="application" src="https://github.com/user-attachments/assets/6d4cd939-b945-4ec3-85f7-b923ac75a493" />


  <h2> </h2>
Passwordless in Okta is not a single toggle. It is the combination of what the authentication policy requires (possession plus user verification) and what the authenticator enrollment policy makes available. If password is still an allowed factor in the rule, users can still choose it.
<h2> </h2>
<img width="780" height="436" alt="Screenshot 2026-10-07 230541" src="https://github.com/user-attachments/assets/218ed453-1ed4-4f59-b5c8-61e214edbc3a" />
<img width="693" height="467" alt="Screenshot 2026-10-07 230605" src="https://github.com/user-attachments/assets/353ad556-79e6-48a1-86a8-c2c4a103fe4a" />
<img width="849" height="487" alt="Screenshot 2026-10-07 230635" src="https://github.com/user-attachments/assets/1e678dbf-30fb-4d8e-b001-a888301cc473" />

 <p><h2> </h2>
<img width="392" height="56" alt="Screenshot 2026-10-07 231647" src="https://github.com/user-attachments/assets/ead66077-d7ff-4ace-9aff-6fa0369a5bba" />
 <p>

