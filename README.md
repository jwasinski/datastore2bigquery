# Export Google Datastore to BigQuery

See this screen recording on YouTube for the demo:

[![YouTube video](https://img.youtube.com/vi/dGyQCE3bWkU/0.jpg)](https://www.youtube.com/watch?v=dGyQCE3bWkU "Google Cloud Datastore to BigQuery")

This script exports a Datastore kind to Cloud Storage, imports it into BigQuery and then deletes the Cloud Storage files.

Usage:

    ./datastore2bigquery.sh PROJECT KIND [BQDATASET] [LOCATION]

Example:

    ./datastore2bigquery.sh code-cooking Food EU

This script requires the `beta`, `bq` and `gsutil` gcloud components, so install those first if you haven't already:

    gcloud components install beta bq gsutil
