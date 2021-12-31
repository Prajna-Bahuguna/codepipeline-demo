# codepipeline-demo
This project uses AWS CodePipeline for CI. 
Source is this Github Repo and build stage picks up buildspec.yml file in root of this repo to take all the json files and dump it to AWS S3 bucket. Moreover it also zips folders, demo-1, demo-2, demo-3 and dump them to different folders in S3.
