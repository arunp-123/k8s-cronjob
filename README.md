# Create a custom  NS:

$ kubectl create namespace my-app

# Create the cronJob

$ kubectl apply -f cronjob.yml

View all CronJobs in a specific namespace:

# kubectl get cronjob -n my-app

Describe CronJob (details):
# kubectl describe cronjob demo-cronjob -n my-app

View Jobs created by the CronJob:
# kubectl get job -n my-app

View Pods created by Jobs:
# kubectl get pods -n my-app


