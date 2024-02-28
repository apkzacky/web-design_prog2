# ABOUT
THIS IS DEMO FOR REAL-WORLD-AUTHENTICATION WEB APP, BUILT IN PHP & MySQL and HTML, Bootstrap-CSS-CDN FOR THE CLIENT SIDE

# FUNCTIONALITY
* SIGNUP (REAL TIME REGISTRATION FUNCTIONALITY)
* SIGNIN (REAL TIME LOGIN FUNCTIONALITY)
* LOGOUT FUNCTIONALITY
* PHPSESSION-ID (cookies) MANAGEMENT (USER CAN STAY LOGIN, WITHOUT RE-ENTERING CREDENTIALS)

# INTALLATION

#### STEP 1 CREATE THE DATABASES 

```sql
CREATE DATABASE authapptest5;
```

#### STEP 2 CREATE THE TABLES

```sql
CREATE TABLE `users` (
  `id` int(11) NOT NULL,
  `username` varchar(30) NOT NULL,
  `email` varchar(50) NOT NULL,
  `password` varchar(255) NOT NULL,
  `reg_date` datetime NOT NULL DEFAULT current_timestamp()
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;
```



# TEAM

  
- Name = Abdifetah Eid Ahmed; Id = Cep/jj/0252/14
- Name = Zakeriye Jamel Muse; Id = Cep/jj/0300/14
- Name = Mahamed mustafe Arab; Id = Cep/jj/0283/14
- Name = Mahamed Bedel abdi;   Id = Cep/jj/287/14
- Name = Mahamed Mahad Muse;   Id = Cep/jj/0282/14
- Name = Yousuf Ibrahim Mohomed; Id = Cep/jj/0299/14

