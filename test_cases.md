# Usernames
1.
gt1098f
gt8957j

2.
gte918x
gta198l
gtr563v

3.
gb38
md1
dk19
vd75

4.
jlang19
azhang88
lzhu91

## Should not be detected (but would be nice)
bg
fhwang 

# Emails
fhwang9@gatech.edu
booboo7@gmail.com

## I want to catch with regex but not sure if reasonably possible
ryao97 @ gatech.edu
azhang88 @ gatech.edu
mdamron @ gatech.edu
random.mail @ mailchimps.com

## Generated fakes
john.doe@company.com
susan_lee@enterprise.org
michael.brown@financecorp.net
hr.department@bigtechsolutions.io
it.support@globex.co
alerts@chasebank-secure.com
service@paypal-update.net
support@wellsfargo.com
noreply@bankofamerica-info.org
transactions@americanexpressmail.com
order-confirmation@amazon.com
support@ebay-payments.net
noreply@shopify-store.org
billing@aliexpress-customer.com
help@etsy-online.co
security@facebookmail.com
noreply@linkedin.com
notifications@twitter-support.org
info@slackhq.net
alerts@dropbox-services.com
secure-update@micros0ft-support.com
noreply@paypa1.com
account-verification@googl3mail.net
support@apple-security-check.info
reset-password@amaz0n-payments.org


# Potential misdetection
[flake8] *I want to raise entropy to detect this rather than exclude a dir* 
extend-ignore = E203
exclude = .git,__pycache__,docs/source/conf.py,old,build,dist
max-complexity = 10

## variable names that are nice to detect
api_key
secret_key
access_token
auth_token
bearer_token
client_secret
private_key
username
user_id
user_email
password
passcode
db_user
db_pass
ftp_password
jwt_token
encryption_key
rsa_private_key
aes_secret
hmac_key
ssl_cert
ssh_key
aws_secret_key
aws_access_key_id
gcp_api_key
azure_client_secret
slack_webhook_url
firebase_secret

## should not be detected
color5 = "9cf001"
brown7 = "7f6e46"

# Very fake keys
AWS_ACCESS_KEY_ID=AKIAIOSFODNN7EXAMPLE
AWS_SECRET_ACCESS_KEY=wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
AZURE_SUBSCRIPTION_KEY=3e5f9b2a6cdd4f44a8b2a7e2f3b4d8e5
GOOGLE_API_KEY=AIzaSyA-1234567890abcdefgHIJKLMNOPQRST


