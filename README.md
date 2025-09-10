# AWS Glue Tutorial

This is a small tutorial project for learning **AWS Glue**.

## Setup

Run the following commands:

```bash
# 1. Clone the repository
git clone https://github.com/AymanAhmediot/TestGlue

# 2. Go into the project folder
cd TestGlue

# 3. Remove placeholder files so the folders are empty
rm data/*/empty.txt
```

## the structur in s3 should be like that 


```
S3
├── athena
├── processedData
├── rawData
│   ├── customers
│   │   └── customers.csv
│   └── orders
│       └── orders.csv
├── scriptLocation
└── tmpDir
```
