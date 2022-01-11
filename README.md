# dynamodb
dynamodb 이모저모


### 자격증명 변경 해야하는경우 -> ./aws/config credential 셋업후.    
import boto3.    
session = boto3.Session(profile_name='targetname').   
db = session.resource('dynamodb').   
