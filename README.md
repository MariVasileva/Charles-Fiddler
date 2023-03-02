# Charles-Fiddler

Ex_0: Сфокусироваться на ниже перечисленных запросах

Protocol: http
IP: 162.55.220.72
Port: 5005


Ex_1: 
Method: GET
EndPoint: /get_method
request url params: 
 name: str
 age: int

response: 
[
    “Str”,
    “Str”
]

Task:
Сделать и в Rewrite, и в BreakPoint (можно отключить чтобы не стопило на каждом запросе)
 ⁃ Подменить url в Charles чтобы в запросе ушло имя которые вы вписали в Postman, а вернулось то, которое вы подставили в Charles.
 
 ![2023-02-15_13-21-43](https://user-images.githubusercontent.com/106372044/222354367-a60eff08-7673-4609-9f2f-79c9fd0da1b7.png)

 ![2023-02-15_13-26-02](https://user-images.githubusercontent.com/106372044/222354426-dbc1c06e-e1f8-4d11-a273-5a29b2005066.png)

 ![2023-02-15_13-26-33](https://user-images.githubusercontent.com/106372044/222354439-af1635e7-392c-483c-8f9a-772e709a1a47.png)


==================


Ex_2:
Method: POST
EndPoint: /user_info_3
request form data: 
 name: str
 age: int
 salary: int

response: 
{'name': name,
          'age': age,
          'salary': salary,
          'family': {'children': [['Alex', 24], ['Kate', 12]],
                     'u_salary_1_5_year': salary * 4}}

Task:
Сделать и в Rewrite, и в BreakPoint (можно отключить чтобы не стопило на каждом запросе)
 ⁃ Подменить body в Charles так чтобы в запросе ушла salary которую вы вписали в Postman, а в u_salary_1_5_year цифра вернулась меньше оригинальной из запроса.
 
 ![2023-02-15_13-19-35](https://user-images.githubusercontent.com/106372044/222354566-4b26a799-ed7b-49ad-ace2-1b70b64321ff.png)

 ![2023-02-15_13-24-35](https://user-images.githubusercontent.com/106372044/222354631-2c3eadec-0c49-4edc-a12c-bd79e1d34159.png)

 ![2023-02-15_13-25-00](https://user-images.githubusercontent.com/106372044/222354652-cfb18f5b-4193-42d4-b48b-de8d8038ac6d.png)

 
==================

Ex_3:
Method: GET
EndPoint: /object_info_1
request url params: 
 name: str
 age: int
 weight: int

response: 
{'name': name,
          'age': age,
          'daily_food': weight * 0.012,
          'daily_sleep': weight * 2.5}

Task:
Сделать и в Rewrite, и в BreakPoint (можно отключить чтобы не стопило на каждом запросе)
 ⁃ Подменить параметры запроса в Charles так, чтобы в Postman пришел ответ где другое name, daily_food > weight из запроса, а daily_sleep < weight из запроса.
 
 ![2023-03-02_12-17-01](https://user-images.githubusercontent.com/106372044/222358059-fd0a96f4-593c-4a76-9ac7-4afe553f7be1.png)

 ![2023-03-02_12-21-40](https://user-images.githubusercontent.com/106372044/222359118-7b08901e-7032-4fd0-bd1e-c452f51f0c72.png)
![2023-03-02_12-22-36](https://user-images.githubusercontent.com/106372044/222359122-2ebb530c-661d-4960-8326-757ec2e04ffe.png)


==================

