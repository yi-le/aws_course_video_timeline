# aws_course_video_timeline

## Official Feedback for Intro

Intro部分的视频，按照Udemy剪辑人员的指导，需要规避在视频中出现课程节数的介绍（关键词：16，13，习题课）。

4分27秒开始至5分07秒，将
```diff
本系列课程
- 一共有16节课组成，13节课
分别介绍各项AWS Services，
- 剩下三节课为模拟考试。其中前13节课服务
内容均来自于亚马逊云官方提供的考试大纲，
- 后三节课的模拟考试考题将完全仿照实际考试的难度、选项、题型、考察内容进行模拟，
方便同学们查缺补漏，达到可以通过亚马逊云考试认证的水平。我们的
- 前13节课
内容包括XXX,XXX,XXX...
```

剪辑修改为
```
本系列课程分别介绍各项AWS Services，内容均来自于亚马逊云官方提供的考试大纲，方便同学们查缺补漏，达到可以通过亚马逊云考试认证的水平。我们的内容包括XXX,XXX,XXX...
```

## Extra Cut

Please acquire subtitled video from 字幕版视频 folder

|Chapter|timestamp|
|-------|---------|
|3-13|1:06|
|4-13|2:24|
|7-5|4:19|
|8-6|2:24|
|9-9|2:30|
|10-6|5:22|

## Acquire Raw Video

Click [this link](https://s3.console.aws.amazon.com/s3/buckets/ascending-aws-association-raw/?region=us-east-1&tab=overview#)

If you are redirected to login in page, please input **595312265488** and click next.

Then input **gloria** under IAM user name tab, then input password and click Sign In button.

Five folders can be found in this page

|Folder Name|Description|
|-----------|-----------|
|AWS LOGO|制作新片头片尾可能会用到的logo等等收尾素材|
|AWS Lecture PPTs|Lecture PowerPoint|
|AWS half (only contents of the lectures)|基本剪好的只有课程内容，无片头片尾的半成片|
|Zoom recordings|桌面及清晰人声录制素材|
|head portrait|人像录制素材|

## Timeline

### Introduction

|Chapter|AWS Lecture PPT Pages|Zoom recordings|head portrait|
|-------|----------------|---------------|-------------|
|01-Intro-ASCENDING|||01-Intro-ASCENDING+02-Intro-ASCENDING-2|
|02-Intro-Ryo|||03-Intro-Ryo|
|03-Intro-Gloria&Yi|||04-Intro-Gloria&Yi|
|04-Intro-AWS-Certification||01-Intro-AWS-Certification(00:12-02:12)|05-Intro-AWS-Certification(00:00-02:00)|
|05-Intro-Course|||06-Intro-Course(00:00-01:34)+(01:46-01:49)|

### Lecture 1

|Chapter|AWS Lecture PPT Pages|Zoom recordings|head portrait|
|-------|----------------|---------------|-------------|
|01-Intro|1|01-Intro+Demo(03:54-04:19)|02-Intro|
|02-EC2-Demo|2|01-Intro+Demo(06:42-15:06)||
|03-Linux-Term|4-6|02-Term-Explaination(00:34-02:58)|03-Term-Explanation(00:00-02:24)|
|04-VPC|7-9|03-VPC(00:14-02:42)|05-VPC(00:00-02:28)|
|05-SSH-Demo||04-SSH-Homework(00:07-02:33)|06-SSH-Demo(00:00-02:26)|
|06-SSH|10-12|04-SSH-Homework(06:55-09:11)|08-SSH(00:00-02:16)|
|07-Security-Group|13-14|04-SSH-Homework(10:00-12:27)|09-Security Group(00:00-02:27)|
|08-Homework|15-17|04-SSH-Homework(13:16-13:51)|10-HW(00:00-00:35), link https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/install-LAMP.html appears on 00:15 |

### Lecture 2

|Chapter|AWS Lecture PPT Pages|Zoom recordings|head portrait|
|-------|----------------|---------------|-------------|
|01-Intro|1-2|01-Intro(01:35-01:55)|01-Intro|
|02-Console-Versus-YAML|3|02-Console-Versus-YAML(2:51-05:31+06:07-06:12)|02-Console-Versus-YAML(00:00-02:40+03:16-03:21)|
|03-Demo-Ending||03-Basic-Components(00:19-00:41)+(01:29-01:35)|03-Demo-Ending(00:00-00:22)+04-Demo-Ending-2|
|04-Basic-Components|4-5|03-Basic-Components(04:22-06:27)|05-Basic-Components(00:07-02:12)|
|05-Basic-Components-2|6-8|04-Basic-Components-2(00:34-05:15)|06-Basic-Components-2(00:02-04:43)|
|06-Demo-Intrinsic-Function||04-Basic-Components-2(06:42-07:45)|07-Demo-Intrinsic-Function(00:03-01:06)|
|07-Amazon-Resource-Name|9|05-Amazon-Resource-Name(00:27-03:09)|08-Amazon-Resource-Name|
|08-Intrinsic-Function-2|10|06-Intrinsic-Function-2(00:16-01:58)|09-Intrinsic-Function-2(00:00-01:42)|
|09-Stack-Status|11-12|07-Stack-Status(00:11-03:24)+(04:05-04:08)+(04:37-05:01)+(05:51-07:02)|10-Stack-Status(00:02-03:15)+11-Stack-Status-2(00:03-00:06)+12-Stack-Status-3(00:01-00:25)+13-Stack-Status-4(00:00-01:11)|
|10-Homework|13-14|07-Stack-Status(07:19-07:47)+(08:15-08:24)|14-Homework+15-Ending|

### Lecture 3
|Chapter|AWS Lecture PPT Pages|Zoom recordings|head portrait|
|-------|----------------|---------------|-------------|
|01-Intro|1|Lecture03(04:03-04:56)|01-Intro|
|02-Cloud-Computing|2-3|Lecture03(06:10-07:36)|02-Cloud-Computing|
|03-Load-Balancer|4-5|Lecture03(08:30-10:13)|03-Load-Balancer(00:00-01:43)|
|04-AutoScaling|6-12|Lecture03(10:47-13:27)|04-AutoScaling(00:00-02:40)(some details need to be modified in the end)|
|05-Advanced-AutoScaling|12-14|Lecture03(14:12-16:55)|05-Advanced-AutoScaling|
|06-Advanced-AutoScaling-2|14-15|Lecture03(17:30-18:34)|06-Advanced-AutoScaling-2|
|07-Demo||Lecture03(20:26-22:04)|07-Demo(00:05-01:43)link https://github.com/overtureLLC/aws_course/blob/master/course3_demo_1.yaml appears on 00:10|
|08-Target-Group|15-20|Lecture03(23:28-26:41)|08-Target-Group(00:00-03:13)|
|09-CloudWatch|20-22|Lecture03(27:22-28:22)|09-CloudWatch(00:00-01:00)|
|10-CloudWatch-2|22|Lecture03(29:31-30:35)|10-CloudWatch-2(00:00-01:04)|
|11-Demo-2||Lecture03(31:03-32:15)|11-Demo-2(00:00-01:12)|
|12-Alarm|23-24|Lecture03(32:50-34:06)|12-Alarm(00:00-01:16)|
|13-CloudTrail|25-27|Lecture03(37:28-38:51)|13-CloudTrail(00:00-01:23)|

### Lecture 4
|Chapter|AWS Lecture PPT Pages|Zoom recordings|head portrait|
|-------|----------------|---------------|-------------|
|01-Intro|1-4|Lecture04(00:28-02:55)|01-Intro(00:00-02:27)|
|02-Demo| |Lecture04(04:13-05:18)| |
|03-AWS-CLI|4-7|Lecture04(05:31-07:55)| |
|04-Demo-2| |Lecture04(09:57-11:47)|04-Demo-2|
|05-AWS-Credentials|7|Lecture04(12:11-12:41)|05-AWS-Credentials(00:03-00:33)|
|06-Demo-3| |Lecture04(13:00-13:53)|06-Demo-3(00:00-00:53)|
|07-Authentication-Chain|7-9|Lecture04(14:08-18:08)|07-Authentication-Chain(00:02-04:02)|
|08-AWS-SDK|10-13|Lecture04(18:32-21:14)|08-AWS-SDK(00:02-02:44)|
|09-Demo-4| |Lecture04(21:40-22:32)|09-Demo-4(00:03-00:55)|
|10-IAM|14|Lecture04(22:51-23:21)|10-IAM(00:00-00:30|
|11-IAM-2|15-16|Lecture04(23:52-24:22)|11-IAM-2(00:00-00:30)|
|12-Demo-5| |Lecture04(24:48-27:44)|12-Demo-5(00:02-02:58)(some details need to be modified in the end)|
|13-IAM-3|17-20|Lecture04(28:05-31:06)|13-IAM-3(00:02-03:03)|

### Lecture 5
|Chapter|AWS Lecture PPT Pages|Zoom recordings|head portrait|
|-------|----------------|---------------|-------------|
|01-Intro|1-2|Lecture05(00:34-03:16)|01-Intro(00:01-02:43)|
|02-Demo|3-5|Lecture05(03:56-08:31)|02-Demo(00:01-04:36)|
|03-Storage-Class|6-10|Lecture05(10:00-13:38)|03-Storage-Class(00:02-03:40)|
|04-Storage-Safety|11-13|Lecture05(14:50-19:19)|04-Storage-Safety(00:01-04:30)|
|05-Demo-2| |Lecture05(20:07-21:05)|05-Demo-2(00:02-1:00)|
|06-S3-CLI|14-19|Lecture05(21:43-28:58)|06-S3-CLI(00:04-07:19)|
|07-Homework|20-21|Lecture05(29:46-28:32)|07-Homework(00:01-00:47)|

### Lecture 6
|Chapter|AWS Lecture PPT Pages|Zoom recordings|head portrait|
|-------|----------------|---------------|-------------|
|01-Intro|1-4|Lecture06(08:15-11:26)|01-Intro(00:01-03:12)|
|02-RDS|5-6+8-9|Lecture06(13:54-18:32)|02-RDS(00:02-04:40)|
|03-RDS-2|7|Lecture06(47:41-50:33)|03-RDS-2(00:11-03:03)|
|04-DynamoDB|10-14|Lecture06(19:40-25:30+30:00-30:05)|04-DynamoDB(00:02-05:52)+05-DynamoDB-2(00:05-00:10)|
|05-Cache|20-22|Lecture06(30:49-34:06)|06-Cache(00:00-03:17)|
|06-DAX|23|Lecture06(38:33-39:50)|07-DAX(00:06-01:23)|
|07-Homework|24-25|Lecture06(44:49-45:23)|08-Homework(00:02-00:36)|

### Lecture 7
|Chapter|AWS Lecture PPT Pages|Zoom recordings|head portrait|
|-------|----------------|---------------|-------------|
|01-Intro|1-6|Lecture07(02:57-08:06)|01-Intro(00:06-05:15)|
|02-Deployment-Strategy|7-12|Lecture07(11:46-21:43)|02-Deployment-Strategy(00:09-10:06)|
|03-Monitoring|13|Lecture07(23:42-24:35)|03-Monitoring(00:05-00:58)|
|04-SQS|14-16|Lecture07(26:00-29:52)|04-SQS(00:02-02:55) potrait recording is shorter than screen recording|
|05-SQS-2|17-21|Lecture07(44:08-48:58)|05-SQS-2(00:02-04:52)|

### Lecture 8
|Chapter|AWS Lecture PPT Pages|Zoom recordings|head portrait|
|-------|----------------|---------------|-------------|
|01-Intro|1-2|Lecture08(00:27-02:49)|01-Intro(00:03-02:25)|
|02-Serverless-Case|3|Lecture08(04:19-06:03)|02-Serverless-Case(00:01-01:45)|
|03-Lambda|4-11|Lecture08(12:04-21:02)|03-Lambda(00:02-09:00)|
|04-API-Gateway|12-14|Lecture08(22:28-25:14)|04-API-Gateway(00:02-02:48)|
|05-Demo||Lecture08(32:34-35:09)|05-Demo(00:08-02:43)|
|06-Conclusion|15-18|Lecture08(36:25-39:17)|06-Conclusion(00:03-02:55)|

### Lecture 9
|Chapter|AWS Lecture PPT Pages|Zoom recordings|head portrait|
|-------|----------------|---------------|-------------|
|01-Intro|1-2|Lecture09(00:11-01:32)|01-Intro(00:02-01:23)|
|02-Cognito|3-4|Lecture09(02:01-03:01)|02-Cognito(00:02-01:02)|
|03-Cognito-2|5-6|Lecture09(04:15-08:09)|03-Cognito-2(00:00-03:54)|
|04-Demo||Lecture09(11:20-17:35)|Show link https://github.com/overtureLLC/AWS_Lab_ApiGateway_Cognito_Lambda at beginning|
|05-Demo-Explaination|7|Lecture09(24:00-24:57)|04-Demo-Explaination(00:03-1:00)|
|06-STS|8-13|Lecture09(25:57-34:00)|05-STS(00:03-08:06)|
|07-KMS|14-15|Lecture09(37:30-39:10)|06-KMS(00:04-01:44)|
|08-SSM|16-17|Lecture09(41:24-43:50)|07-SSM(00:02-02:28)|
|09-SNS|18-22|Lecture09(45:59-48:45)|08-SNS(00:04-02:50)|

### Lecture 10
|Chapter|AWS Lecture PPT Pages|Zoom recordings|head portrait|
|-------|----------------|---------------|-------------|
|01-ECS|1-8|Lecture10(00:23-09:05)|01-ECS(00:01-08:43)|
|02-Content-Delivery|9-10|Lecture10(10:01-11:45)|02-Content-Delivery(00:02-01:46)|
|03-Demo||Lecture10(14:09-20:00)||
|04-CloudFront|12|Lecture10(22:07-24:01)|04-CloudFront(00:01-01:55)|
|05-Route53|13-16|Lecture10(24:58-27:53)|05-Route53(00:04-02:59)|
|06-OpsWorks|17-22|Lecture10(28:32-34:23)|06-OpsWorks(00:01-05:52)|

### Lecture 11
|Chapter|AWS Lecture PPT Pages|Zoom recordings|head portrait|
|-------|----------------|---------------|-------------|
|01-Cloud9|1-3|Lecture11(00:28-02:45)|01-Cloud9(00:03-02:20)|
|02-CodeBuild|4-7|Lecture11(04:00-09:06)|02-CodeBuild(00:02-05:08)|
|03-CodeDeploy|8-11|Lecture11(21:39-25:20)|03-CodeDeploy(00:02-03:43)|
|04-CICD|12-14|Lecture11(26:36-29:35)|04-CICD(00:01-03:00)|
|05-CICD-2|15-18|Lecture11(34:17-39:10)|05-CICD-2(00:01-4:54)|
|06-CICD-3|19|Lecture11(46:54-49:46)|06-CICD-3(00:05-02:57)|
|07-CodeStar|20-22|Lecture11(54:16-55:44)|07-CodeStar(00:01-01:29)|
|08-Demo||Lecture11(56:00-59:18)+(60:57-62:26)|07-CodeStar(01:45-05:03)+(06:42-08:11)|
|09-Homework|23-24|Lecture11(68:00-68:37)|08-Homework(00:01-00:38)|
|10-Ending||Lecture11(69:58-70:32)|09-Ending(00:01-00:35)|