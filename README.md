# ERD FOR THE GYM WEBSITE

<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188878857-1c5f83f8-a99a-44fa-865b-c311cbf267b6.png" width="800" height="580"/></p>



# RELATIONAL MODEL (MAPPING)

<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188879480-0d1644f7-cc80-4763-a051-d93b94582daf.png" width="650" height="650"/></p>


# Database Design


1. Membership table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892285-391a0768-ae62-49ba-ac1d-c623c0820615.png" width="600" height="300"/></p>

2. Customer table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892312-0ec633d9-14ae-47f5-8597-420790503f45.png" width="600" height="300"/></p>

3. Customer_phone_number table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892331-37eebf10-4cab-4afd-b7f7-144ec8f622dc.png" width="600" height="150"/></p>

4. Measurments table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892347-f3aa80e8-b726-4cda-8e15-1407c2314e29.png" width="600" height="200"/></p>

5. Trainer table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892382-20b00ded-920e-4d08-ad6c-3c04a6af8ed2.png" width="600" height="300"/></p>

6. trainer_phone_number table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892408-e9726651-5535-4044-93c4-0468eb7c4f25.png" width="600" height="150"/></p>

7. Class table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892441-55cd2249-d87e-4945-8c27-dad8a239a887.png" width="600" height="300"/></p>

8. take_class table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892454-c8b254cf-04c4-4716-a3b4-bc028fc69164.png" width="600" height="200"/></p>

9. exercises_reports table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892472-0e551cbf-8b3e-4bb9-bbe2-d9717f9e47c7.png" width="600" height="200"/></p>

10. managing_exercises_reports table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892493-f827cbd3-1042-4151-bf70-6284b1ead8f4.png" width="600" height="150"/></p>

11. viewing_exercises_reports table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892506-c70d8c26-693f-4f2c-8d6e-db396f6c44b2.png" width="600" height="150"/></p>


# Select Statements


1. Membership table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892566-dd7fa874-e13f-42eb-9c75-201cac49a129.png"/></p>

2. Customer table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892579-60b6c699-70c3-4fe1-9a41-80fb25e9945f.png"/></p>

3. Customer_phone_number table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892606-b5461118-b39f-4d77-a48c-906c56f8d619.png"/></p>

4. Measurments table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892632-618ba0b0-6ddf-4237-943e-29a994d3d383.png"/></p>

5. Trainer table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892652-2b835e55-06ae-4798-8a5d-21f3ba3fc21c.png"/></p>

6. trainer_phone_number table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892671-c5259e28-d67e-4dd3-86b4-b0065427ab31.png"/></p>

7. Class table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892697-7451a932-72a5-447f-980e-8c5349bf7da1.png"/></p>

8. take_class table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892719-bfcb414f-6699-455f-bdcb-b2f76191cc8d.png"/></p>

9. exercises_reports table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892736-90ca309b-bae2-42a1-85b5-f9a58c48e53f.png"/></p>

10. managing_exercises_reports table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892760-1096e415-503b-4717-9a38-6849531518ed.png"/></p>

11. viewing_exercises_reports table
<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188892776-1734a48f-4584-4775-9d3d-c9190678154e.png"/></p>

# CLASS DIAGRAM

<p align="justify">
This is class diagram. It is about <b>online gym website</b>.
We have 11 classes: <b>User, trainer, Customer, phone_number, measurements, membership, class, take_class, exercises_reports, managing_exercise_reports, viewng_exercise_reports</b>. Each class consist of attributes and methods.
<p>

<p align="justify">
The <b>User</b> is the generalized form of <b>trainer</b> and <b>Customer</b>. These two classes can have the attributes and methods of the <b>user</b> class as well as their own attributes and methods. The <b>User</b> class is the parent class while the <b>trainer</b> and <b>customer</b> classes are the child classes.
The <b>Customer</b> and <b>phone_number</b> have the composition relationship, that means the <b>phone_number</b> class cannot exist without the <b>Customer</b> class.
Also, The <b>trainer</b> and <b>phone_number</b> have the composition relationship, that means the <b>phone_number</b> class cannot exist without the <b>trainer</b> class.
Also, The <b>customer</b> and <b>measurements</b> have the composition relationship, Therefore, the <b>measurements</b> class cannot exist without the <b>customer</b> class.
there is varied types of relationships.
there is a "many to many" relation between <b>customer & exercises_reports, trainer & exercises_reports, customer & class</b>, and because of that we breaked these relations by using "association" relationship.
</p>

<p align="center"><img src="https://user-images.githubusercontent.com/85819577/188888454-c02e8ce4-b4d2-418e-a5f1-a55e675e2602.png" width="750" height="700"/></p>

