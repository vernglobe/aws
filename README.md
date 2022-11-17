How to use?

Install from npm:
npm i @vernglobe/aws

```ts

import aws from "@vernglobe/aws";

await aws("CloudWatch", "putMetricData", params);

await aws(DYNAMODB_DOC_CLIENT, "put", {
  TableName: membershipTbl,
  Item: item,
});

await aws("S3", "putObject", {
  Bucket: bucketName,
  Key: key,
  Body: buf,
  ContentEncoding: "base64",
  ContentType: type,
});

```