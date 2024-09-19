# OS Group Assignment

## Team Members:

#### Add your names here:
0. Rishabh Mittal
1. Malladi Pradyumna
2. Anirudh Bagalkotker
3. Kartik Pandey
4. Dhruv Arora
#### Architecture Design:
![image](https://github.com/MSSRPRAD/Graph_Database/assets/97427342/b0733790-8795-4074-9c0a-befb35d47418)

## Setup Instructions:

```
## Run Secondary Server 1 and 2
gcc src/secondary_server.c -o secondary_server && ./secondary_server 1
gcc src/secondary_server.c -o secondary_server && ./secondary_server 2

## Run Load Balancer
gcc src/load_balancer.c -o load_balancer && ./load_balancer

## Run Client
gcc src/client.c -o client && ./client
```
