# cloudwatch-logs-to-es

Streaming CloudWatch Logs Data to Amazon Elasticsearch Service:

You can configure a CloudWatch Logs log group to stream data it receives to your Amazon Elasticsearch Service (Amazon ES) cluster in near real-time through a CloudWatch Logs subscription. For more information, see https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/CWL_ES_Stream.html


This Lambda function code transforms your incoming CloudWatch Logs data to index documents and submits them to your Elasticsearch cluster. You can modify this function to add custom data transformations (for example, converting IP addresses to geo-locations)
