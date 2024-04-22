# Identity and Access management


Authentication answers the question, "Are you who you say you are?" Authorization answers the question, "What actions can you perform?"

## IAM features:

- Global - IAM is global and not specific to any one Region. You can see and use your IAM configurations from any Region in the AWS Management Console.
- Integrated with AWS Services - IAM is integrated with many AWS services by default.
- Shared access - You can grant other identities permission to administer and use resources in your AWS account without having to share your password and key.
- MFA - IAM supports MFA. You can add MFA to your account and to individual users for extra security.
- Identity federation - IAM supports identity federation, which allows users with passwords elsewhere—like your corporate network or internet identity provider—to get temporary access to your AWS account. 
- Free to use - Any AWS customer can use IAM; the service is offered at no additional charge.

## IAM best practices:

- Lock down the AWS root user.
The root user is an all-powerful and all-knowing identity in your AWS account. If a malicious user were to gain control of root-user credentials, they would be able to access every resource in your account, including personal and billing information. To lock down the root user, you can do the following:

  - Don’t share the credentials associated with the root user.
  - Consider deleting the root user access keys.
  - Activate MFA on the root account.

- Follow the principle of least privilege. Least privilege is a standard security principle that advises you to grant only the necessary permissions to do a particular job and nothing more. To implement least privilege for access control, start with the minimum set of permissions in an IAM policy and then grant additional permissions as necessary for a user, group, or role.
- Use IAM appropriately. IAM is used to secure access to your AWS account and resources. It provides a way to create and manage users, groups, and roles to access resources in a single AWS account. IAM is not used for website authentication and authorization, such as providing users of a website with sign-in and sign-up functionality. IAM also does not support security controls for protecting operating systems and networks.
- Use IAM Roles when possible. Maintaining roles is more efficient than maintaining users. When you assume a role, IAM dynamically provides temporary credentials that expire after a defined period of time, between 15 minutes and 36 hours. Users, on the other hand, have long-term credentials in the form of user name and password combinations or a set of access keys. User access keys only expire when you or the account admin rotates the keys. User login credentials expire if you applied a password policy to your account that forces users to rotate their passwords.
- Consider using an identity provider
- Regularly review and remove unused users, roles and other credentials

