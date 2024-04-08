docker run --name filter-clogging-lambda --platform linux/amd64 -p 9000:8080  filter-clogging-demo:v1



aws ecr get-login-password --region ap-south-1 | docker login --username AWS --password-stdin 599517396273.dkr.ecr.ap-south-1.amazonaws.com


599517396273


Numeric value '"{\ruleNodeId\"":\""c7d83290-bc59-11ee-97a1-13eb5634dd40\"",\""ruleChainId\"":\""c22b2ea0-7b64-11ee-8' is not recognized