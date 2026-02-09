# AWS Service - Role (for Exam)

so you can create a role to use in a service like EC2 instance

so select the trusted entity first (the service)
then Role permission or policy
Verify

IAM security tools

- IAM Credentials Report (account-level)
  - Report that lists all your accounts users and the status of their various Credentials
- IAM / Credential Report / Download (a CSV file)
  - To check MFA works
  - Rotation

- IAM Access Advisor (user-level)
    Access advisor shows the service permissions granted to a user and when those serices were last accessed
    You can use this information to revise your policies.
    you can check wich service you can access.

BEST PRACTICES / GUIDELINES

- Don't use the root account except for AWS account setup
- One physical user = One AWS user
- Assign users to groups and assign permissions to groups
- Create a strong password policy
- Use and enforce the use of Multi Factor Auth (MFA)
- Create and use Roles for giving permissions to AWS Services
- Use Access Keys for Programmatic Access (CLI / SDK)
- Audit permissions of your account using IAM Credentials Report & IAM Access Advisor.
- Never share IAM uses & Access Keys
