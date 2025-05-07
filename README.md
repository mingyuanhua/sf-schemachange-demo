# sf-schemachange-demo

You need to set up [Repository secrets] in [Secrets and Variables] under [Settings] tab of the repository.

Here is the list of all secrets.
- PASSPHARSE
- SNOWFLAKE_ACCOUNT
- SNOWFLAKE_DATABASE
- SNOWFLAKE_PRIVATE_KEY_CONTENT
- SNOWFLAKE_ROLE
- SNOWFLAKE_SCHEMA
- SNOWFLAKE_USER
- SNOWFLAKE_WAREHOUSE

## Key Takeaway
There is a trick to set up SNOWFLAKE_PRIVATE_KEY_CONTENT. 

You can follow the steps in this [Closed GitHub Issue](https://github.com/Snowflake-Labs/schemachange/issues/269). 

You will need to store the rsa_key_pkcs8_base64 for the SNOWFLAKE_PRIVATE_KEY_CONTENT secret.
