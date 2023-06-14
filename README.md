# Mend-demo

## Jenkins Integration Notes

Two options to store the “key” information
- Global Properties
- Local Pipeline script in the “environment” section

The examples shown use the global properties. Make sure you create the following keys and populate their values:

* WS_APIKEY (Integration -> Organization APIKEY from your production organization)
* WS_USERKEY (User Profile -> User Keys section from your production organization)
* WS_WSS_URL (https://<Mend URL>/agent)

## Ref:
- [SCA Overview](https://docs.mend.io/bundle/sca_user_guide/page/sca_overview.html)