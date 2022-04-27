gcloud builds submit --tag gcr.io/predict-348516/predict-new  --project=predict-348516

gcloud run deploy --image gcr.io/predict-348516/predict-new --platform managed  --project=predict-348516 --allow-unauthenticated
