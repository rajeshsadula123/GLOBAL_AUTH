# Global and Instance Authorization
Method **get_global_authorizations** in RAP Application

**What is Authorization in RAP**

Authorization control in RAP protects your business object against unauthorized access and operations (Create, Update, Delete). 
Authorization control is always relevant when the permission to execute an operation depends on the role.

In RAP each read or modify request can be checked via authorization objects against user roles before the request is finally executed

# Global Authorization

Global authorization is used for all authorization checks. You can define global authorization to check if users are allowed to execute an operation in general (CREATE, UPDATE, DELETE). authorization master (global)
Instance Authorization

# Instance Authorization

Instance authorization is used for all authorization checks, in addition to the user role. With instance authorization, you can define authorization on a field or operation (UPDATE, DELETE). Instance authorization is only possible for instance-based operations. authorization instance ()


# Implementation

**Step 1**

Add global keyword in Behavior Definition file.

Define global authorization in the behavior definition and implement it in the behavior implementation class

<img width="699" height="359" alt="image" src="https://github.com/user-attachments/assets/d1ab47d9-535c-432f-9cba-b88860917237" />

Method get_global_authorizations --> Not added any code ( By defalut having access to all operations like Create/Edit/Delete ).

<img width="918" height="374" alt="image" src="https://github.com/user-attachments/assets/417f9bd9-10a0-4c18-b9ea-596775ce5c27" />


