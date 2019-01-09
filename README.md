# CloudFormation Workshops

![Cloudformation logo](https://s3.amazonaws.com/bdrbucket/cloudformation-logo.png)

Hello, This is AWS Cloudformation Workshop, please follow the instruction in  the workshops.

## Lab1 Tools for JSON & YAML

**Jason Editor**  
https://jsoneditoronline.org/

**Jason 2 Yaml**  
https://www.json2yaml.com/
 
 **Example:**
 <table>
 <tr>
 [
  {
    "type": "string",
    "name": "Issue Description",
    "value": "Between 3:05 AM and 3:15 AM PDT we experienced an Internet connectivity issue with an external provider outside of our network which may have intermittently affected traffic between some end-user networks and the CN-NORTH-1 Region. Connectivity to instances and services within the Region was not impacted by the event. The issue has been resolved and connectivity has been restored. "
  },
  {
    "type": "string",
    "name": "Impacted Systems/Tools",
    "value": "N/A"
  },
  {
    "type": "string",
    "name": "Impacted Service",
    "value": "International connectivity"
  },
  {
    "type": "string",
    "name": "Symptom",
    "value": "The traffic between some end-user networks and the CN-NORTH-1 Region may be affected intermittently.\r\n"
  },
  {
    "type": "list",
    "name": "Impacted Region(s)",
    "value": [
      "cn-north-1"
    ]
  },
  {
    "type": "string",
    "name": "Impacted support level",
    "value": "All"
  },
  {
    "type": "string",
    "name": "Known impacted accounts",
    "value": "N/A"
  },
  {
    "type": "string",
    "name": "Action Taken",
    "value": "LSE dashboard call initiated, joined the call and verified this issue  has restored."
  },
  {
    "type": "string",
    "name": "Related TT#",
    "value": "https://tt.amazon.com/0107403055"
  },
  {
    "type": "string",
    "name": "Related Case#",
    "value": "N/A"
  },
  {
    "type": "string",
    "name": "LSE Call (dashboard/ops) info",
    "value": "Harbinger Event: http://harbinger.amazon.com/event/2026"
  },
  {
    "type": "string",
    "name": "Next step of actions and timeline",
    "value": "N/A"
  }
]
 </tr>
 </table>


## Lab2 Parameter Exercise

**Parameter Example:**  
https://s3-us-west-2.amazonaws.com/cfn-bootcamp-2018/Json/Lab2.json 

![Parameter 1](https://s3.amazonaws.com/bdrbucket/F5473861-9FCB-4154-A9E9-34EC1B3EBB37.png)

**Parameter Group Example:**  
https://s3-us-west-2.amazonaws.com/cfn-bootcamp-2018/Json/Lab2-ParameterGroup.json

![Parameter 2](https://s3.amazonaws.com/bdrbucket/FB52B621-E7F4-426D-93CB-AD9EEA6B93C5.png)


## Lab3 ChangeSet Exercise

**Origigal Example:**  
https://s3-us-west-2.amazonaws.com/cfn-bootcamp-2018/Json/Lab2.json

![Parameter 1](https://s3.amazonaws.com/bdrbucket/F5473861-9FCB-4154-A9E9-34EC1B3EBB37.png)

**Change Set Example:**  
https://s3-us-west-2.amazonaws.com/cfn-bootcamp-2018/Json/Lab2-Changeset.json

![Parameter 1](https://s3.amazonaws.com/bdrbucket/F5473861-9FCB-4154-A9E9-34EC1B3EBB37.png)
--------------------------
![Parameter 2](https://s3.amazonaws.com/bdrbucket/33D0205E-6526-4DBB-9DA4-82392B85DD68.png)
--------------------------
![Parameter 3](https://s3.amazonaws.com/bdrbucket/2A7DA25F-5B58-4781-8F71-611F1FBA6B97.png)
--------------------------
![Parameter 4](https://s3.amazonaws.com/bdrbucket/8527CE86-C446-4AF0-ADDA-425744AE6F1E.png)

## Lab4 A Wordpress stack with bootstrapping
https://s3-eu-west-1.amazonaws.com/cloudformation-templates-eu-west-1/WordPress_Single_Instance.template

![Parameter 5](https://s3.amazonaws.com/bdrbucket/4BDFDA64-296A-4DEE-A738-7F280977825A.png)


## Lab5 Wait Condition and CreatePolicy
Check The diffirence:  

1. **Creationpolicy:** http://bit.ly/2peUQTJ  
2. **WaitCondition:** http://bit.ly/2pvjMql
 


