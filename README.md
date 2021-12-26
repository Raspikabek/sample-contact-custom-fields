# Sample Unlocked Package - Custom fields on Contact Object for Salesforce

This is a sample Salesforce Unlocked Package.

## How to install

### Option 1

1. Clone the repository
2. Execute the following command from within the cloned repository

```sh
sfdx force:package:install -p "RaspiSampleContactCustomFields@1.0.0-0" -r -w 30 -u <TARGET_ORG_ALIAS>
# for additional info of the command run `sfdx force:package:install --help`
```

### Option 2

Simply excute the command:

```sh
sfdx force:package:install -p 04t1i0000010etJAAQ -r -w 30 -u <TARGET_ORG_ALIAS>
# for additional info of the command run `sfdx force:package:install --help`
```

## Grant access to users

```sh
sfdx force:user:permset:assign -n rd_Sample_Contact_Custom_Fields -u <USERNAME>
# for additional info of the command run `sfdx force:user:permset:assign --help`
```
