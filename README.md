# <h1 style="font-size: 32px;">Shipment Management System</h1>
### <h5 style="font-size: 24px;">Demo Video Link - <a href="https://youtu.be/TnrahnLE7Kw?si=3NsZgPi2jMFcC-Zf" target="_blank">https://youtu.be/TnrahnLE7Kw?si=3NsZgPi2jMFcC-Zf</a></h5>


## <h2 style="font-size: 24px;">Introduction</h2>

<p style="font-size: 18px;">The Shipment Management System allows users to create, update, and view shipment records through a web interface. It communicates with a backend API to store and retrieve data from a database. This project serves as an example of integrating frontend forms with backend API calls using JavaScript and AJAX.</p>

## <h2 style="font-size: 24px;">Features</h2>

<p style="font-size: 18px;">
- Create new shipment records with details such as Shipment No., Description, Source, Destination, Shipping Date, and Expected Delivery Date.<br>
- Update existing shipment records.<br>
- Retrieve and display shipment details based on the Shipment No.<br>
- Reset form functionality to clear input fields.<br>
</p>

## <h2 style="font-size: 24px;">Technologies</h2>

<p style="font-size: 18px;">
- **Frontend**: HTML5, CSS3, Bootstrap, JavaScript (jQuery)<br>
- **Backend**: Custom backend API (HTTP), integrated with a database (not provided in this repository)<br>
- **Deployment**: Vercel (for deployment of frontend)<br>
</p>

## <h2 style="font-size: 24px;">Installation</h2>

<p style="font-size: 18px;">
To run the project locally, follow these steps:
1. Clone the repository:<br>
   ```bash
   git clone https://github.com/Shelbybosss/JsonPowerDB-ShipmentManagement-Form.git<br>
   cd shipment-management-system

## <h2 style="font-size: 24px;">ScreenShots</h2>

![Screenshot 2024-07-10 180629](https://github.com/Shelbybosss/JsonPowerDB-ShipmentManagement-Form/assets/102911609/f8ea5400-9fea-464c-8965-b74cb8d6d010)
<br>
![Screenshot 2024-07-10 180701](https://github.com/Shelbybosss/JsonPowerDB-ShipmentManagement-Form/assets/102911609/c32ad69c-118e-4963-88b9-6f9666413d34)
<br>
![Screenshot 2024-07-10 180728](https://github.com/Shelbybosss/JsonPowerDB-ShipmentManagement-Form/assets/102911609/e5a47a7f-f508-4c88-9cc8-803881545748)
<br>
![Screenshot 2024-07-10 180804](https://github.com/Shelbybosss/JsonPowerDB-ShipmentManagement-Form/assets/102911609/b713dca4-5717-496b-948f-319fc1517809)

## <h2 style="font-size: 24px;">CRUD And usefull commands</h2>
<pre>
```GET
{
    "token": "90931714|-31949214282530301|90963650",
    "cmd": "GET",
    "dbName": "Employee",
    "rel": "EmpRel",
    "jsonStr":{
      "name": "Suhas"
    }
}
```
</pre>

<pre>
```PUT
{
  "token": "90931714|-31949214282530301|90963650",
  "cmd": "PUT",
  "dbName": "Employee",
  "rel": "EmpRel",
  "jsonStr": {
    	"name": "Suhas",
        "email": "suhasmagar273@gmail.com"
  }
}
```
</pre>

<pre>
```REMOVE
{
    "token": "90931714|-31949214282530301|90963650",
    "cmd": "REMOVE",
    "dbName": "Employee",
    "rel": "EmpRel",
    "record": 2,
    "jsonStr" : {}
}
```
</pre>

<pre>
```UPDATE
{
    "token": "90931714|-31949214282530301|90963650",
    "cmd": "UPDATE",
    "dbName": "Employee",
    "rel": "EmpRel",
    "jsonStr":{
      "1": {
        "name":"Shelby"
    		}
		}
}
```
</pre>

<pre>
```GET_BY_KEY
{
    "token": "90931714|-31949214282530301|90963650",
    "dbName": "Employee",
    "cmd": "GET_BY_KEY",
    "rel": "EmpRel",
    "createTime": true,
    "updateTime": true,
    "jsonStr": {
        "name": "Thomas"
    }

}
```
</pre>

<pre>
```GET_BY_RECORD
{
    "token": "90931714|-31949214282530301|90963650",
    "dbName": "Employee",
    "cmd": "GET_BY_RECORD",
    "rel": "EmpRel",
    "record": 6,
    "createTime": true,
    "updateTime": true
}

```
</pre>



<pre>
```PUT_ALL
{
    "token": "90931714|-31949214282530301|90963650",
    "cmd": "PUT_ALL",
    "dbName": "Employee",
    "rel": "EmpRel",
    "jsonStr": [
      {
        "name": "Soniya",
        "email": "soniya@gmail.com",
        "mobileno": "9967825671"
      },
      {
        "name": "Thomas",
        "email": "Thomas@gmail.com",
        "mobileno": "123456789"
      }
      {
        "name": "Tommy",
        "email": "Tommy@gmail.com",
        "mobileno": "789456123"
      }
      {
        "name": "Munna",
        "email": "Munna@gmail.com",
        "mobileno": "4562478961"
      }
      ]
}
```
</pre>
