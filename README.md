# Login into mysql server using putty.
```
git clone https://github.com/rajalingarao/3.12.expense-app-infra-standard-shellscript.git
```
```
cd 3.12.expense-app-infra-standard-shellscript
```
```
sudo sh mysql.sh
```

# Login into backend server
ssh ec2-user@backend.lithesh.shop
```
git clone https://github.com/rajalingarao/3.12.expense-app-infra-standard-shellscript.git
```
```
cd 3.12.expense-app-infra-standard-shellscript
```
```
sudo sh backend.sh
```

# Login into frontend server
ssh ec2-user@frontend.lithesh.shop
```
git clone https://github.com/rajalingarao/3.12.expense-app-infra-standard-shellscript.git
```
```
cd 3.12.expense-app-infra-standard-shellscript
```
```
sudo sh frontend.sh
```
# Trouble shoot the mysql server:
```
mysql -h mysql.lithesh.shop -u root -pExpenseApp@1
```

how check logs of application:
```
sudo cat /var/log/messages
```