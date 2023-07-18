- 👋 Hi, I’m @Rigi1313
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Rigi1313/Rigi1313 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
from json.encoder import INFINITY
from urllib import response
import requests
import time
while True :        
        url ="https://www.clubhouseapi.com/api/join_channel"
        payload =                 
        token=[ 
"fc3d7bec1520d0867b8242e695fb109313b0df1f",
"8b4c045490095cb8a17c478017b137cd02466de5",
"da40773a0a0341803bc8e8dbd73f19669869edc0",
"7b1e4d210af6e4e1d1df8787380591371ddb6c33",
"4902f269f148a50b54d037823b775b192f5f1ac6",
"e0b3d4862568a123afa1e751b9a2e58c7dadcf3f",
"f51ebe2da0fd21753d136710cafd9fe8e33d0aa0",
"26423428a112b21ca4df95157ff2fc075472449b",
"f3a3ca82ffc49ba19941667678b18152b45a41fb",
"034dbe295ccdc3f0f7b3a1cbd538eb134aab2c64",
"b0bf9b6f837d981f805e117b6009d95000666235",
"ca915933c65341c070ab3bd377819dc08ca85df0",
"579ad8aae1b66cf99ee2f85c4a6acc74e0a6fbce",
"a97f379e5684b1d9ca33c007e15844928f1a04c4",
"35f6d479a3e2f2b1dbd5b38ba93dd5c5562a361d",
"190a51c7e47bc1816b2edd69fb0ab859fe426fe6",
"064e5e7703b68afaf082ea191147e8d4dcc610c7",
"38f4287d6136788df8745577eaf35a78b78df996",
"722f321afea209677e5cc6ac53d3856be16239a7",
"20b84c5d8e92ddf134d34ab615168a27d1120bea",
"cf9e97519001df9ecffe17112a5441208fa7dbf4",
 "eb85f15113dc4dcfe41d37be7356848a788c2353",
 "c60533187b4e11e4e490245acad48be6c93a854d",
 "fd2a9c4fa5709a4fd526eced53e9ca304b15f727",
 
]
        for i in range(800):
                headers = {
'CH-Languages': 'en-US',
'CH-Locale': 'en_US',
'Accept': 'application/json', 'Accept-Encoding': 'gzip, deflate',
'CH-AppBuild': '2090',
'CH-AppVersion': '12.5.5',
'CH-UserID':'553220940',
'User-Agent':"clubhouse/2029(android/11/MIUI Global 12.5.5)",
'Connection': 'close',
'Content-Type': 'application/json; charset=utf-8',
'Authorization': 'Token '+token[i]
                }
# 200 is count
                response = requests.request("POST", url, headers=headers, data=payload)

                print(response.text)
                time.sleep(0)
