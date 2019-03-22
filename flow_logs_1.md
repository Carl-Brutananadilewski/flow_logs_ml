# Using Amazon VPC Flow Logs for Predictive Security Analytics

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>


<p align="center">
  <img src="images/01_no_waf.png">
</p>

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>


<p align="center">
  <img src="images/02_with_waf.png">
</p>

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

## Web Application Firewall

<br>
<br>

WAF can control how API Gateway, Amazon CloudFront or an Application Load Balancer responds to web requests.

<br>
<br>
##Protects from:
<br>
* Cross-site scription
* Source IP
* Geo Location
* Query string
* SQL injection
* Headers and query strings

## VPC Flow Logs
<br>
<br>
 Feature that enables you to capture information about the IP traffic going to and from network interfaces in your VPC

 <br>
 <br>
 <br>

* Stores logs in CloudWatch
* Can be enabled on:
  * Network interface
  * Subnet
  * VPC
* Each network interface has unique log stream

 <br>
 <br>
 <br>

 <p align="center">
   <img src="images/03_flowlogs.jpeg">
 </p>

 <br>
 <br>
 <br>

## AWS SageMaker
<br>
<br>
Amazon SageMaker is a fully managed machine learning service.
<br>
<br>
<br>
<p align="center">
  <img src="images/04-sagemaker-architecture.png">
</p>
<br>
<br>
<br>

### Jupyter Notebook

<br>
<br>

Notebook documents are documents that contain both computer code (e.g. python) and rich text elements (paragraph, equations, figures, links, etc…). Notebook documents are both human-readable documents containing the analysis description and the results (figures, tables, etc..) as well as executable documents which can be run to perform data analysis.

https://github.com/Carl-Brutananadilewski/flow_logs_ml/blob/master/sm-notebook.ipynb
