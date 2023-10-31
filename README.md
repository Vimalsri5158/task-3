# task-3

** 1. for the given JSON iterate overall for loops (for , for in, for of, forEach)**


**i.JSON Object:-**

	const jsonData = 
       {
       		 "name": "John",
       		 "age": 30,
       "city": "New York"
      };


**ii. JSON Array:-**

	const jsonArray = 
       [
       			 { "name": "John", "age": 30, "city": "New York" },
       			 { "name": "Alice", "age": 25, "city": "Los Angeles" },
       		 	{ "name": "Bob", "age": 35, "city": "Chicago" }
      ];

**iii. For Loop:-**

	for (let i = 0; i < jsonArray.length; i++) 
     {
  		console.log(jsonArray[i]);
      }

**iv. for in loop:-**

	for (let key in jsonData) 
       {
       		 console.log(key, jsonData[key]);
      }

**v. for of loop:-**

	for (let obj of jsonArray) 
       {
        		console.log(obj);
      }

**vi. For Each:-**

	jsonArray.forEach(item => {
 		 console.log(item);
    });


    

**2.Create your own resume data in JSON format**

{
 		 "name": "Vimalraj",
 		 "title": "Software Engineer",
  		"contact": {
   			 "email": "vimalsriq4911@gmail.com",
    			"phone": "7094292251",
    			"github": "github.com/Vimalsri5158"
 				 },

    "summary": "Experienced software engineer with a strong background in web development, JavaScript, and Python. 
              Passionate about creating efficient and scalable software solutions. Proven track record of delivering high-quality code on time and on budget.",

    "experience": [
        {
          "position": "Senior Software Engineer",
          "company": "Tech Solutions Inc.",
          "location": "Chennai",
          "startDate": "January 2018",
          "endDate": "Present",
          "responsibilities": [
            "Led a team of developers in the design and implementation of a complex web     application.",
            "Developed and maintained key components of the company's flagship product.",
            "Collaborated with cross-functional teams to deliver high-impact features and improvements."
          ]
        },
        {
          "position": "Software Developer",
          "company": "InnovateTech",
          "location": "Chennai",
          "startDate": "June 2020",
          "endDate": "December 2023",
          "responsibilities": [
            "Designed and implemented front-end solutions for multiple projects using HTML, CSS, and JavaScript.",
            "Collaborated with back-end developers to ensure seamless integration of user interfaces with server-side logic.",
            "Participated in code reviews and provided mentorship to junior developers."
          ]
        }
      ],
      
    "education": 
      [
        {
          "degree": "Bachelor of Engineering ",
          "school": "C.S.I. High School",
          "location": "Salem",
          "graduationDate": "May 2018"
        }
      ],

      
    "skills": [
        "JavaScript",
        "Python",
        "React",
        "Node.js",
        "HTML/CSS",
        "Git-Hub"
      ],
      
    "languages": ["English (Fluent)", “Hindi”],
  
     "interests": [
          "Open-source projects",
          "AI and Machine Learning",
          "Hiking",
          "Photography"
          ]}



**3.Codekatta:-  **
      https://www.guvi.in/code-kata
