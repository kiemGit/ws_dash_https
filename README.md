

# stucture file
	nginx-node-docker/
	├── Dockerfile
	├── docker-compose.yml
	├── wsdash.work.gd.key
	├── wsdash.work.gd.cer
    ├── ca.cer
	├── server.js
    ├── package.json

# run server
    docker-compose up -d

# test using postman app, click [New] butoon, select [WebSocket] menu, paste script ass bellow, after paste link ass bellow, click [Connect] button
    wss://wsdash.work.gd.

# test send data, select [Message] tab, paste script bellow, and then click [Send] button  
    {
    "trsID": "17240000003",
    "code": "34799250174090121201",
    "name": "Hakim 1",
    "platNumber": "B555",
    "reason": "Test Reason",
    "lup": "
    2022-03-01 13:49:16"
    }



