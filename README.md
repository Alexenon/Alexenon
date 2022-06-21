# Hi everyone, I'm Alex <img height="30px" width="30px" src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Hi.gif">

#### This is my codewars account level and points <br>
[<img align="left" alt="Code Wars Badge" src="https://www.codewars.com/users/AleXeNeoN/badges/large"/>][codewars]

<br><br><br>

```
USE [MASTER]
GO
IF EXISTS (SELECT * FROM sys.databases WHERE NAME='Test_Database')
BEGIN
	ALTER DATABASE Test_Database SET SINGLE_USER
	WITH ROLLBACK IMMEDIATE
	DROP DATABASE Test_Database
END
GO

CREATE DATABASE Test_Database
GO
USE Test_Database
GO

ALTER AUTHORIZATION ON DATABASE :: Test_Database TO SA
GO


 
CREATE TYPE Default_String FROM NVARCHAR(20) NOT NULL
CREATE TYPE Long_String FROM NVARCHAR(500) NOT NULL
GO


CREATE TABLE Users (
	Id_User INT PRIMARY KEY, 
	Name Default_String,
	Age INT DEFAULT 18,
	Salary INT DEFAULT NULL,
	UniqueField INT,
	CHECK(Age >= 18 AND Age <= 120),
	CHECK(Salary BETWEEN 0 AND 100000),
	UNIQUE(UniqueField, Age)
)
GO


CREATE INDEX idx_users ON Users(Id_User, Salary)


BACKUP DATABASE Coffee_Time
	FILE = 'Coffee_Time' 
	TO DISK = 'Coffee_Time.bak'   
	WITH FORMAT, 
	STATS = 10,
	DESCRIPTION = 'Full backup for Coffee_Time database'
GO


----------------------------
/* Synonim for start hour */
----------------------------
CREATE SYNONYM start_hour
FOR Employers_Schedule.start_work_hour
GO 
```


I'm a beginner developer that loves to study 🖥💡
- 📝 I regulary write documentation for my code
- 💻 I use daily **.js**, **.java**, **.py**,  **.sql**
- 📖 I am currently learning java frameworks
- 💬 Talking is like a breath of fresh air after a long programming session
- 👯 We can connect to play some games of Chess ♟

<br>

<i>“What's the difference between a good programmer and a bad one” — No comments</i>


### Languages and Tools that I know:

<img align="left" alt="Visual Studio Code" title="Visual Studio Code" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" style="padding-right:10px;" />
<img align="left" alt="IntelliJ IDEA" title="IntelliJ IDEA" width="26px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9c/IntelliJ_IDEA_Icon.svg/2048px-IntelliJ_IDEA_Icon.svg.png" style="padding-right:10px;" />
<img align="left" alt="HTML5" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" style="padding-right:10px;" />
<img align="left" alt="CSS3" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" style="padding-right:10px;" />
<img align="left" alt="JavaScript" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" style="padding-right:10px;" />
<img align="left" alt="MySQL" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" style="padding-right:10px;" />
<img align="left" alt="PostgreSQL" width="26px" src="https://cdn.iconscout.com/icon/free/png-256/postgresql-11-1175122.png" style="padding-right:10px;" />
<img align="left" alt="Git" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" style="padding-right:10px;" />
<img align="left" alt="GitHub" width="26px" src="https://user-images.githubusercontent.com/3369400/139447912-e0f43f33-6d9f-45f8-be46-2df5bbc91289.png" style="padding-right:10px;" />

<br>
<hr>


<!-- My most used languages -->
<img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Alexenon&theme=dark&border_radius=10" />


### What I want to learn in near future:

<img align="left" alt="Node.js" title="Node.js" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" style="padding-right:10px;" />
<img align="left" alt="MongoDB" title="MongoDB" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" style="padding-right:10px;" />
<img align="left" alt="React" title="React" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" style="padding-right:10px;" />
<img align="left" alt="Gatsby" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gatsby/gatsby-original.svg" style="padding-right:10px;" />
<img align="left" alt="GraphQL" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/graphql/graphql-plain.svg" style="padding-right:10px;" />


<br>
<hr>


<!-- My github stats -->
<img src="https://github-readme-stats.vercel.app/api?username=Alexenon&show_icons=true&theme=github_dark&line_height=30&border_radius=10&hide=stars" />


### Connect with me:

<!-- Image hyperlinks that contains adresses -->
[<img align="left" alt="Alexenon | Vk" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/vk.svg" />][vkcom]
[<img align="left" alt="Alexenon | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />][instagram]
[<img align="left" alt="Alexenon | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linked-in]







<!-- Links to my social media -->
[vkcom]: https://vk.com/hazzardy
[instagram]: https://www.instagram.com/hazzarddy
[linked-in]: https://www.linkedin.com/in/alex-xenon-14900a22a/
[codewars]: https://www.codewars.com/users/AleXeNeoN
