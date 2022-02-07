https://programmer.group/docker-installs-jira-and-confluence-cracked-version.html


docker build -t wangzan18/jira:latest .

docker build -t konan/jira:latest .


docker run -d --name jira\
  --restart always \
  -p 8080:8080 \
  -e TZ="Asia/Seoul" \
  -m 4096M \
  -v jira:/var/atlassian/jira \
  konan/jira:latest




java -jar atlassian-agent.jar \
  -d -m test@test.com -n BAT \
  -p jira -o http://127.0.0.1:8080 \
  -s BG23-0RAU-HQ0E-KHIV

java -jar atlassian-agent.jar \
  -d -m test@test.com -n BAT \
  -p jira -o http://10.10.18.18:8080 \
  -s BEZF-O140-4BJU-2Y95


java -jar atlassian-agent.jar \
  -d -m test@test.com -n BAT \
  -p jira -o http://10.10.18.18:8081 \
  -s B9TV-80UI-V9NM-CBM0



