Cloudflare Pages project that updates a Cloudflare Gateway Egress Policy

In order to setup this use case, the following environmental variables need to be added in the dashboard:
- RULE_ID : this is the rule id for the particular Cloudflare Gateway Egress policy we would like to modify;
- ACCOUNT_ID : the cloudflare account id (make this a secret variable)
- USER_EMAIL : API Key user email (make this a secret variable)
- API_KEY : the API Key (make this a secret variable)

The egress IPs should be modified in the function script directly.

