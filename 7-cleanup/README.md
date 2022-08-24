
# Dọn dẹp tài nguyên

Chúng ta sẽ tiến hành các bước sau để xóa các tài nguyên chúng ta đã tạo trong bài thực hành này.

#### Xóa Auto Scaling Group:

-	Truy cập EC2 Management Console
-	Trên thanh điều hướng bên trái, chọn Auto Scaling Groups
-	Chọn Auto Scaling Group liên quan tới bài lab.
-	Click Delete
-	Gõ delete vào ô trống và nhấn delete

#### Xóa Load Balancer:
-	Truy cập EC2 Management Console
-	Trên thanh điều hướng bên trái, chọn Load Balancers
-	Chọn Load Balancer liên quan tới bài lab.
-	Click Actions.
-	Click Delete.
#### Xóa Target Group:
-	Truy cập EC2 Management Console
-	Trên thanh điều hướng bên trái, chọn Target Groups
-	Chọn Target Group liên quan *tới bài lab.
-	Click Actions.
-	Click Delete.
-	Click Yes, delete
#### Xóa Launch Template:
-	Truy cập EC2 Management Console
-	Trên thanh điều hướng bên trái, chọn Launch Templates
-	Chọn Launch Template liên quan tới bài lab.
-	Click Actions.
-	Click Delete template
-	Gõ delete vào ô trống và nhấn delete
#### Xóa AMI:
-	Truy cập EC2 Management Console
-	Trên thanh điều hướng bên trái, chọn AMIs
-	Chọn AMI liên quan tới bài lab.
-	Click Actions.
-	Click Deregister.
-	Click Continue.
#### Terminate EC2 instance:
-	Truy cập EC2 Management Console
-	Trên thanh điều hướng bên trái, chọn Intances
-	Chọn tất cả EC2 Instance liên quan tới bài lab.
-	Click Actions.
-	Click Manage Instance State.
-	Chọn Terminate.
-	Click Change State
#### Xóa DB Instance
-	Truy cập RDS Management Console
-	Trên thanh điều hướng bên trái, chọn Databases
-	Chọn tất cả DB Instance liên quan tới bài lab.
-	Click Actions.
-	Click Delete
-	Bỏ chọn Create final snapshot? và chọn I acknowledge that upon instance deletion, automated backups, including system snapshots and point-in-time recovery, will no longer be available
-	Gõ delete me vào ô trống.
-	Click Delete
#### Xóa VPC + subnet + security group:
-	Truy cập VPC Management Console
-	Trên thanh điều hướng bên trái, chọn Your VPCs
-	Chọn VPC liên quan đến bài Lab
-	Click chọn Action
-	Click Delete VPC
-	Gõ delete vào ô trống
-	Click Delete
#### Xóa Cloudfront Distribution
- Truy cập Cloudfront Management Console
- Trên thanh điều hướng bên trái, chọn Distribution
- Chọn Distribution liên quan đến bài lab
- Chọn Delete
