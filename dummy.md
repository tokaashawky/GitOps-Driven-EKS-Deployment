sqp_37b8fd663fb56cff3fdfa589ee60a5911ef25a11

token of project

# if jenkins fails 
sudo apt clean
sudo du -sh /var/lib/jenkins/workspace
sudo rm -rf /var/lib/jenkins/workspace/*
docker system prune -af
sudo systemctl start jenkins
sudo systemctl status jenkins


# NodeJs
- sudo apt update && sudo apt upgrade -y

- sudo apt install -y curl ca-certificates gnupg

- curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -

- sudo apt install -y nodejs



