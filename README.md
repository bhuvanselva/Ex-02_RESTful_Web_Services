# Ex-02_RESTful_Web_Services

**BHUVANESHWARI 212222220008***
## Aim:

To create, deploy and execute RESTful Web service programs using Server, Client and Client-Side remote invocation
## Procedure:

### Server side:
Step 1: Create a new Java Web Project. Follow Steps 1-5 as in SOAP Based Web Service.
Step 2: Right-click on the project name and select New->RESTful Web Services from Patterns.
```
![276879648-d373199d-6217-44b5-a1b8-b46a9e9c4896](https://github.com/user-attachments/assets/f50252e2-7dc8-4e12-bca2-72fefcab98b1)
```




Step 3: A new window will appear. Select “Simple Root Resource” and click Next.
```
![276879668-31f7efbd-ba9f-4ee9-966e-ffb0d31e54a3-1](https://github.com/user-attachments/assets/ddf95c28-9a0a-4f7e-9cb1-739101e2020a)

```
 
 


Step 4: In the next window, give a Resource Package name and choose MIME Type as “text/html”. Click Finish.
```
![276879698-eb5725c3-989a-4098-9356-cccafb12c7f8-1](https://github.com/user-attachments/assets/01295fba-1f34-4585-a1a2-3298c01cfa28)

```


Step 5: Two editing tabs will appear. Close “ApplicationConfig.java”. You need to write all your required functionalities in GenericResource.java.
Step 6: Alter getHtml() method as shown below.
Step 7: Save your project, clean and build it. Deploy your project.
```
![276879804-881e6734-33db-4e61-8232-c3c1cd3ad0f5-1](https://github.com/user-attachments/assets/aab49a4d-86df-42f0-bbf3-e65a0e998fd1)

```
 

 


Step 8: To test your web service, open a new browser window/tab and type the URL as http://localhost:8080/project_name/webresources/generic?params=45&params=35 and hit enter. (This is the easiest way of testing the web service when it makes use of List).



Client-Side:


Step 1: Create a new Java Web Project. Follow steps 1-5 as in section 1.1.
```
![276879895-2221286d-88c5-4730-9e5c-9441905ed41a](https://github.com/user-attachments/assets/99543d8d-d063-4bf0-8272-4da1096d0f56)

```



Step 2: Right-click on the project and select New->RESTful Java Client.




Step 3: A new window will appear. In that, give a name to your client, a package name and select “From Project” under the “Select the REST resource:” tab and click Browse. Step 4: Carefully select your RESTful resource (web service) and click OK.
Step 4: Carefully select your RESTful resource (web service) and click OK.
```
![276879952-b71689de-9318-4b2a-ba33-657b60ebea08-1](https://github.com/user-attachments/assets/12d72681-5c0e-49fb-95f5-b32d1793f919)

```

 


Step 5: Once everything is filled, the New RESTful Java Client window should look like this. Click Finish.
```
![276879972-5a638789-76cd-4e6e-8e0d-93f2e680c939-1](https://github.com/user-attachments/assets/8ffedd61-3c40-4245-a42f-294aa3a55677)

```




Step 6: An editing tab will open. Alter getHtml() method with the following.

```
![276880038-4076da6b-ee79-4ffe-82f3-63daa536b853](https://github.com/user-attachments/assets/81858239-eef7-47d1-bfd8-222845d4f597)
```
 
 


Step 7: Right-click on the Libraries folder under your project and select “Add JAR/Folder”.

```
![276880407-f565676e-bf24-4f2c-9035-83d957e0f11f-2](https://github.com/user-attachments/assets/4e9471f7-7c37-416c-8165-8d1a4fd0251f)
```


Step 8: A new window will appear. Navigate to the folder where you have placed the “javax.ws.rs-api2.0.1.jar” file and select Open.

```
![276880423-1ea59045-7880-415d-a7d6-180a8b0a8435-1](https://github.com/user-attachments/assets/ffb3c96e-9024-4104-896b-e9ce547ec912)
```




 
 


Step 9: Right-click on the Web Pages folder and select JSP. In the new window, give a name to the JSP page and click Finish.
Step 10: A new tab will appear with the default contents of the JSP page. In that, include at the top and type the following code to invoke the client java code.

```
![276880444-4a668af1-7a9d-485d-ab47-d400a7742a1b-1](https://github.com/user-attachments/assets/59bba0ea-e3e1-4fcb-be81-32d8cf647953)
```






Step 11: Save the project and build it.
Step 12: Run the JSP file and you should see the output in a new browser window.
```
![276880501-5783c8d6-6573-4f4d-ac38-b43c35b94702-1](https://github.com/user-attachments/assets/bd2ce1ba-04d1-4b71-937b-ddcfaefbf56f)
```


Client-Side Remote Invocation:


Step 1: Follow steps 1-5 as in Section 2.2
Step 2: In the generated NewJerseyClient.java file, Replace BASE_URI from private static final String BASE_URI = "http://localhost:8080/RESTful_Server/webresources"; TO private static final String BASE_URI = "http://192.168.116.62:8080/RESTful_Server/webresources";
Step 3: Follow steps 6-12 as in Section 2.2


## Result:
 Thus, the RESTful web service program has been successfully created and executed.
