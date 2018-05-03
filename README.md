# AWS Certified Solutions Architect - Associate (February 2018) Exam Experiences

2 day's before i passed my Certified Solutions Architect - Associate Exam with Score 80% , i take the new exam "AWS Certified Solutions Architect - Associate (Released February 2018)" , exam was 65 question scenario based questions time 130 min and more than enough i finished my exam and still have 60 min time , exam depend on good understand to AWS services when and where yo use each services my preparation for the Exam :

A cloud Guru Course very useful time them 2 times

FAQ very important to read

white paper for the new exam

Whizlabs Exams very useful

for topic came to my exam

lambda

S3

EBS many question , you should know when you use each volume type

Amazon ECS

VPC , you need to understand it very well

EC2

Elastic Cache

Amazon RDS , you need to understand it very well

DynamoDB

Redshift

Cloud trail

cloud Watch

SNS , SQS

From <https://acloud.guru/forums/aws-certified-solutions-architect-associate/discussion/-KqTvkfGo3cmjxW0dWU2/exam_notes_from_today> 


 

I passed the new solutions architect associate exam (Feb 2018) yesterday. It was a bit harder than I expected but manageable. By the time I took the exam, I was regularly scoring ~93-95% on the acloud exam simulator, but only scored a 76% on the actual exam, so I'd expect a drop of about 10-15% going into it.

The acloud.guru course is great, but I definitely wouldn't rely on it solely to pass unless you're already fairly familiar with aws services. You should read a lot of the FAQs and whitepapers, and most importantly do the labs.

I've been studying for about a month, maybe slightly less, and had zero experience with aws before starting this course. It helped that I've been using aspects of it in my daily work, but not a lot of that came up.

The questions in the exam itself were very detail oriented, often the answer to a question changed from what you'd intuitively think because of how they worded it and the details they included. My advice here would be to very thoroughly read over all questions and go back over the exam at least 2-3 times. Time wasn't an issue since they give you 2 and a bit hours to answer 65 questions.

For anyone curious about result release, you get a pass or fail instantly, and a more detailed breakdown 1-5 business days later (mine came the next day).
Good luck.

From <https://acloud.guru/forums/aws-certified-solutions-architect-associate/discussion/-KqTvkfGo3cmjxW0dWU2/exam_notes_from_today> 

 

 
I just successfully sat and passed the most recent version of the AWS CSA-A released in February 2018. 65 questions, 130 Minutes. Here's my synopsis.

Key Points:
- 100% of questions are scenario based
- Need to have a solid understanding of Multi-tiered architecture for applications.
- Need to understand Hybrid Environments (On-Premise/Off-Premise)
- Questions are not too wordy, but.. can be almost silly in their scenarios.
- Most questions have 2 answers that are blatantly wrong (if you know the concepts well), and then you have to thoughtfully choose 1 of the other 2.
- There's Plenty of time.

Topics:
- Lots of questions on EFS - Understand use, and comparison to EBS and S3
- Lots of questions on RDS
- Lots of questions on ELBs. Specifically, ALBs and Classic ELBs, and choosing which, when.
- Quite a few questions on KMS, encryption, choosing what product when. Understand all options/scenarios synced with S3.
- Several questions on Dedicated instance types for EC2, again what to choose/when scenario
- Several on EBS Types, and needing to choose the correct type - SSD, Provisioned IOPs, Throughput Optimized
- Several on/with VPC Endpoints
- Several on Cloud Watch and Cloud Trail - API tracks, Flow Logging, Metrics, etc
- 5+ on Lambda
- 5+ on DynamoDb (Including one involving DAX)
- 2+ on Kinesis
- 2-3 on Docker
- 2-3 API Gateway
- 1 on Redshift
- AWS Glue was one option
- VPCs and subnet structure. Including communication between them, with ELBs, and off-premise.
- of course security groups and use, as well.

From <https://acloud.guru/forums/aws-certified-solutions-architect-associate/discussion/-L5WLPO18o4lj0LrIbA_/passed_february_2018_csa-a_exa> 
 
 

 
A big thank you to Ryan and crew! My exam prep was entirely acloudguru and the recommended FAQs and white papers. I did have some prior AWS experience, but not nearly enough to pass the exam.

Things I wish I knew more about:

RedShift - I had at least 4 (maybe 5 )questions about it, included encryption, cross-region

Classic Load Balancers - know the difference between classic and application load balancers

Things I knew but felt were worth mentioning:

EBS - I knew EBS but was surprised how many questions there were asking me to pick the best variant of EBS

SQS - multiple questions

SNS - one question

VPC - how to talk to non-AWS resources, multiple scenarios

S3 - encryption, pre-signed URLs

Database bottlenecking questions

Multiple Lamda questions

API Gateway

EFS

Sadly, DR MC GIFT PX was unneeded. But once seen, he cannot be unseen. lol

I'm going to keep the momentum going and take the Dev exam soon since there's so much overlap.

From <https://acloud.guru/forums/aws-certified-solutions-architect-associate/discussion/-LArIK5gwGmcXkNEj9z_/passed_the_exam_yesterday> 

 

 
SQS (task prioritization, how many queues is good to have), Spot instances pricing (e.g. what much you get billed after 75mins), what services are natively encrypted, valid sources for Origin servers in CloudFront, ECS instance from default AMI and how to troubleshoot if resources do not come up, STS vs IAM roles (if a company wants to rotate credentials bi-weekly and employees not to have any creds), lots of DB questions - e.g. what is suitable for GPS navigation service, which DB scales best, etc.

From <https://acloud.guru/forums/aws-certified-solutions-architect-associate/discussion/-KaHhsSrrDOdoZPU0zcz/cleared_the_aws_csa_with_87%25_!> 
 


 
Congrats Tocacar! I just passed mine this morning as well! I agree, unexpected significant presence of Redshift questions. Also, expectedly however, a fair number of scenario questions - maybe 6 - 10, it seemed - on setting up websites with webservers, elb, and databases, and how the subnets and AZs should be configured for high availability. As the ACG course says, you need to know VPC and all the networking components really well.

From <https://acloud.guru/forums/aws-certified-solutions-architect-associate/discussion/-LANRw5kcN4lUVi_2nq2/passed_the_solution_architect> 

 

 
I passed SAA on the 16th of April. I got 85% (pass threshold was 72%)

I liked the exam as there were no:
- lengthy scenarios
- things you have to memorize

There were interesting concise real-life scenarios instead.

Please find some resources that might help you get more points.

https://aws.amazon.com/about-aws/whats-new/2016/11/access-your-amazon-glacier-data-in-minutes-with-new-retrieval-options/

https://docs.aws.amazon.com/elasticloadbalancing/latest/application/introduction.html#application-load-balancer-benefits

https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/raid-config.html

https://aws.amazon.com/premiumsupport/knowledge-center/migrate-nat-instance-gateway/

https://aws.amazon.com/lambda/faqs/#Securityandaccess_control

There were also many quite challenging questions about hybrid architectures and migration to the cloud.
If you have any questions please feel free to ask.

From <https://acloud.guru/forums/aws-certified-solutions-architect-associate/discussion/-LAMzA9wLFtrJZScZ8o0/solutions_architect_-_associat> 

 

 
Yesterday I passed the SA Associate Exam (Feb 2018); one month ago I passed Developer Associate. I've been doing AWS on the job for about two years, but the services used weren't very complex - certainly not even 10% of the stuff you see in these certifications.

I'm not going to give you questions on the exam if only because my brain is too small to remember questions like that, but perhaps I can help by giving you an idea of what to expect and my experience.

First of all, Developer Associate was much harder, in my experience. I only scored in the [edit:] mid-high 70's for that one. That's because it has a lot more raw memorization questions, such as a couple of API-related ones, and number limit-related questions. Personally I think that stuff isn't useful, because on the job you can quickly look up APIs or account / region / service limits.

Solutions Architect was a lot more rational in terms of the questions they asked. It was less tricky than A Cloud Guru or other questions I saw online. No offense meant to ACG: the ACG course material was what I relied on the most; I just have to add that ACG's questions had more painful curveballs. In particular, the Mini-Quiz was brutal so don't despair if you fail (they're challenging in a good way though, since you can learn from being asked complex scenario questions). In the final exam in the course I scored around 80%, while in the exam room I scored 91% with no studying in between.

Bottom line: Amazon questions are clear, the English grammar and clarity are perfectly crisp and if I wasn't sure about something, it honestly felt like it was my fault and not the fault of the question being ambiguous.

Solution Architect was more around scenarios than Developer -- many, many scenarios -- with you faced with client-facing decisions. For example, a client has a web app with a database back-end, and wants to add redundancy to his setup. How would you do this in the most COST EFFECTIVE way.

This is critical: the question (asked without caps ;-) ) is going to present a problem for you as a consultant / Solutions Architect, and then ask you to solve the problem with the criteria that it either be the most performant (eg. cost doesn't matter), the most cost-effective, or the most resilient. There may have also been 'the most secure' manner. That's the format of I'd say a huge portion - possibly a 1/5 or 1/4 of the questions.

In terms of samples, I'll tell you right now that serving a web site from S3 is a lot more cost effective than using EC2 instances. Yes, that came up on the exam at least once or twice. Kinesis came up in a scenario question about taxis (or something) needing to stream location data. Then you have the EBS types, and the number 500 MB/s came up at least three times. So know all those inside and out, including provisioned IO and such.

There are security questions (rightfully so) as well.

* Critical bottom line review tip * Understand the different use cases for the services that overlap. One obvious example is NAT Gateway v. Instance, but a less obvious one is DynamoDB v. RDS v. Redshift. If something looks similar to another thing, immediately hone in on it (that's how I'd use the FAQ, instead of reading a FAQ at the end or cramming like that).

Don't worry about the 'Well Architected Framework' - the presentation (both Amazon's, the whitepaper and ACG's) were brutally painful and boring and generally consists of common sense for anyone who's worked in Architecture. Read it quickly, that's it.

Also don't kill yourself reviewing every FAQ suggested - you'll study for 1 year if that happens. See my comment above.

Finally - stay away from Brainseed Testing Centers. My experience was very negative, starting when I arrived 20 minutes early for my 1 pm only to stand in the hallway with a bunch of very angry and nervous test takers for 1 hour and 10 minutes - yes, my test started at around 1:45 pm, which by that time I was furious (because they'd triple booked the test takers, most of whom were not Amazon). Moreoever, it was noisy, I was sitting next to the door with people coming in and out, the chair was broken... I lodged an official complaint with Amazon.

Questions:

Candidate Score: 916

The AWS Certified Solutions Architect - Associate (Released February 2018) (SAA-C01) has a scaled score between 100 and 1,000. The scaled score needed to pass the exam is 720.

Section 1.0: Design Resilient Architectures 34%

Section 2.0: Define Performant Architectures 24%

Section 3.0: Specify Secure Applications and Architectures 26%

Section 4.0: Design Cost-Optimized Architectures 10%

Section 5.0: Define Operationally-Excellent Architectures 6%

I got a "Needs Improvement" on Section 4.0; sounds like I'm not very good at keeping it cheap. ;-)

From <https://acloud.guru/forums/aws-certified-solutions-architect-associate/discussion/-L92JwoRgLdhC-umnwEO/passed_feb_2018_version_of_sol> 
 

 
 
First time taking the exam. To prepare, I went through the course, read the Security and Storage Whitepapers, FAQs for some services, especially VPC and RDS. I took the mini-quiz and practice exam on my SA Exam mobile app, getting 85-90%. Did not do as well on the Scenario Quiz, which I could not even finish (ending up with 60% I think). Some of those questions were much harder than the actual test. I built the VPC-Subnet-IG-NAT setup on my own right after that chapter, and then did it again the week before taking the test. That helped with knowledge and confidence.

One thing that helped was to take the quizzes, and for services where I got things wrong, review the FAQs. I also skimmed over the Security and Storage Whitepapers the day of the exam (after having read them in full). Doing this helped me answer a few questions. I forgot to read the Lambda FAQ and may have missed a question on that.

Overall score 85%

Designing high-available, cost-efficient systems: 86%

Implementation/Deployment: 60%

Data Security: 100%

Troubleshooting: 80%

There were 55 questions, and all seemed scenario-based, so maybe the "beta" exam launched earlier this year in in production? I had plenty of time to answer the questions. I did review some and changed an answer or two on review. There was even a question early in the test that was answered by the scenario of a later question.

I should have brushed up more on API Gateway and ECS.

Thank you Ryan and A Cloud Guru team for making such an interesting course.

From <https://acloud.guru/forums/aws-certified-solutions-architect-associate/discussion/-L1ZhIJd21pIeHyL90_C/passed_the_csaa_today!> 
 

 
 
I passed the CSA Associate exam today with 58%. There were quite a few unexpected questions regarding Cassandra Clusters, VPC Configurations, etc. But overall I studied to understand and not for the exam. There were questions regarding Bastian Hosts, VPC, NAT Instance, NAT Gateway, Kinesis, etc. Pay more attention to VPC and ELB as there were many questions on them. Good luck!

From <https://acloud.guru/forums/aws-certified-solutions-architect-associate/discussion/-L1ZhIJd21pIeHyL90_C/passed_the_csaa_today!> 
 
 
 
 
I passed my SAA today. This course was helpful. Thanks to Ryan and Cloud guru team. Had many questions about ASG and ELB. Highly recommend reading white papers especially security ones and faqs. Couple of questions about VPC, Kinesis, SQS, SNS, ECS, S3 concepts. Overall I had a good experience, learned a lot of new things with this certification prep. Good luck to all of you!

From <https://acloud.guru/forums/aws-certified-solutions-architect-associate/discussion/-L1ZhIJd21pIeHyL90_C/passed_the_csaa_today!> 