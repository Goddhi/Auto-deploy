

cd .circleci/files
aws cloudformation deploy \
--template-file cloudfront.yml \
--stack-name initial-stack \
--parameter-overrides WorkflowID=udapeople-3488383


DB instance identifier
udapeople222
password: udapeople123
master username: postgres
Database name: udapeople222