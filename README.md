# netdata-monitoring-Docker

**
mkdir netdata-monitoring
cd netdata-monitoring


**for running netdata on docker conatainer
docker run -d \
  --name=netdata \
  -p 19999:19999 \
  --cap-add SYS_PTRACE \
  --security-opt apparmor=unconfined \
  netdata/netdata


**local host
http://localhost:19999


**GIt Commands

git init
git add .
git commit -m "Initial commit with Netdata monitoring setup"
git remote add origin https://github.com/shreyashpatil4266/netdata-monitoring-Docker.git
git branch -M main
git push -u origin main




