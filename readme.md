## Learn Node Starter Files

## Sample Data

To load sample data, run the following command in your terminal:

```bash
npm run sample
```

If you have previously loaded in this data, you can wipe your database 100% clean with:

```bash
npm run blowitallaway
```

That will populate 16 stores with 3 authors and 41 reviews. The logins for the authors are as follows:

|Name|Email (login)|Password|
|---|---|---|
|Wes Bos|wes@example.com|wes|
|Debbie Downer|debbie@example.com|debbie|
|Beau|beau@example.com|beau|

## Run on Aws

to run the application you need to download the .pem file if you are a labber you can found it in lvl drive on:

tech program 2.0/2019/suppliers/awskey/supplierTempKey.pem

once you download it open command line and execute this command to connect to aws ec2 machine:

```bash
ssh ec2-user@34.230.67.89 -i <.pem file path> 
```

once you are connected to aws machine to start supplier service execute:

```bash
cd LVLProviders
node start.js
```


