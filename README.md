# Quiz Templte html Based
This template has support 4 types quiz 
1.Multiple Choice 
2.True or False
3.Matching
4.Choose Multiple Answers 

Introduction:-
This quiz template expected data in json.The json format will be below format only
Example:-

var questions = [{
  "questionType":"Matching",
  "question":"match the following countries with their cities",
  "correct":"1@1 2@2 3@3",
  "choices":["INDIA@1 AUSTRLIA@2 ENGLAND@3","CANBERRA@2 LORDS@3 HYDERABAD@1"]
  },{"questionType":"Multiple Choice","question":"What is capital of India ?","correct":1.0,"choices":["Hyderabad","Delhi","Gujarath","Mumbai"]},{
  "questionType":"Matching",
  "question":"match the following Technologies with Developer ",
  "correct":"1@2 2@3 3@4 4@1",
  "choices":["JAVA@1 JavaScript@2 Spring@3 Hibernate@4","Red_Hat_Software@1 Brendan_Eich@3 Pivotal_Software@4 James_Gosling@2"]
},
{"questionType":"True or False ","question":"Java is object oriented programing language ?","correct":0.0,"choices":["True","False"]}
];
