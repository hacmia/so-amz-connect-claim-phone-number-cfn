# so-amz-connect-claim-phone-number-cfn

# https://stackoverflow.com/questions/75389664/claim-an-amazon-connect-phone-number-with-aws-cloudformation/76289739#76289739

Started with a new Clean Account
01. Created Instance using CFN (MyFirstInstance) - (success)
02. Claimed Phone number using CFN (success)
03. Tried to Claim new Phone Number in Console (Limit Reached Error)
04. Checked Service Quota - Amazon Connect
05. Checked Service Quota - List Phone Numbers (Only one phone number claimed)
05-1. Updated - Claimed Phone number CFN stack (success) (No Screenshot)
06. Deleted - Claimed Phone number CFN stack
07. Checked Service Quota - List Phone Numbers (List is now empty)
08. Deleted - Instance CFN Stack
09. ReCreated Instance using CFN (MyFirstInstance) - (success)
10. ReClaimed a Phone number using CFN (failed with did not stabalize error)
11. Tried to Claim new Phone Number in Console (Limit Reached Error)
11-1. Deleted both Stacks (No Screenshot)
12. ReCreated Instance using CFN (new logical id MySecondInstance) (success)
13. ReClaimed a Phone number using CFN (new logical id - MySecondPhoneNumber) - (failed with did not stabalize error)

Did you ever create, then delete an instance in your account?
