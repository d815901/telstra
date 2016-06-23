# *  Obtain these keys from the Telstra Developer Portal
CONSUMER_KEY="your consumer key"


# * ApiKey header value should be in the format of "xxx" where xxx is the CONSUMER_KEY

ADBOR_ID="266388948"
CONSUMER_KEY="<CONSUMER_KEY>"
curl -X GET \
curl -H "apiKey: $CONSUMER_KEY" \ 
-H "Content-Type: application/json" \

"https://api.telstra.com/v1/serviceQualification/service-addresses?adborId=$ADBOR_ID"
