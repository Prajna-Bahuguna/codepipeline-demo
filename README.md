# codepipeline-demo
AWS CodePipeline used to achieve Continuous Integration. It takes all the '.json' files in this repo and put it in the json-folder path in AWS S3.
Moreover, it takes all the respective folders, demo-1, demo-2, demo-3, creates their zip and put them to respective paths in S3 as mentioned in builspec.yml. Pipeline triggers when there is a new commit in the repo and updates the files in S3.
