# AWS IoT Core rules

This repo contains all the rules for AWS IoT Core used by Agromate

## Structure

- mqtt_hour_message_to_db: Save the hourly message in DynamoDB without any lambda
- mqtt_month_media: Pass the message at mqtt_lambda that save media of month and delete all previous measuration from DynamoDB