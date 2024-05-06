# Blood Glucose with data granular

Dataset: Blood Glucose Event - Body Health

Data: "blood_glucose_mg_per_dL_int"

Data Sources: Dexcom

## Frame dataset

```Json
{
  "client_uuid": "demoClientUUID",
  "user_id": "demoUserId",
  "version": 2,
  "document_version": 1,
  "auto_detected": false,
  "data_structure": "blood_glucose_event",
  "body_health": {
    "events": {
      "blood_glucose_event": [
        {
          "non_structured_data_array": [
            {}
          ],
          "metadata": {
            "datetime_string": "2023-12-29T21:07:14.402999Z",
            "sources_of_data_array": [
              "Polar"
            ],
            "user_id_string": "demoUserId",
            "was_the_user_under_physical_activity_bool": true
          },
          "blood_glucose": {
            "blood_glucose_avg_mg_per_dL_int": 0,
            "blood_glucose_granular_data_array": [
              {
                "datetime_string": "2023-12-29T21:07:14.402999Z",
                "blood_glucose_mg_per_dL_int": 0
              }
            ]
          }
        }
      ]
    }
  }
}
```
