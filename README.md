#  AWS VPC and Subnet Automation (Boto3)

A simple Python script that programmatically creates a VPC and subnets on AWS using the `boto3` SDK. Ideal for learning AWS automation, scripting infrastructure setup, or rapid prototyping in the af-south-1 (Cape Town) region.

---

##  Features

-  Creates a new VPC (`10.0.0.0/16`)
-  Adds two subnets (`10.0.1.0/24` and `10.0.2.0/24`)
-  Applies a custom VPC tag (`Name = my-vpc`)
-  Lists all VPCs and their CIDR block association states

---

##  Project Structure

```
main.py           # Main automation script
requirements.txt  # Python dependency list
```

## Quickstart

**1. Install dependencies**
```
   pip install -r requirements.txt
```

**2. Set AWS Credentials**
```
aws configure
```

**3. Run the Script**
```
python main.py
```

## Output Example
```
vpc-eabcd12345efg6789
{'State': 'associated'}
```
