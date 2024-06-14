# Blood Glucose with data granular

Dataset: Blood Glucose Event - Body Health

Data: "blood_glucose_mg_per_dL_int"

Data Sources: Dexcom

## Frame dataset

![descarga (23)](https://github.com/SalvatoreCordano/DataStructure/assets/147050219/f273c977-017c-474f-b294-c70e9c60517c)


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
              "Dexcom"
            ],
            "user_id_string": "demoUserId",
            "was_the_user_under_physical_activity_bool": true
          },
          "blood_glucose": {
            "blood_glucose_avg_mg_per_dL_int": 0,
            "blood_glucose_granular_data_array": [
              {
                "datetime_string": "2024-04-25T12:00:00.000Z",
                "blood_glucose_mg_per_dL_int": 120
              },
              {
                "datetime_string": "2024-04-25T12:30:00.000Z",
                "blood_glucose_mg_per_dL_int": 130
              },
              {
                "datetime_string": "2024-04-25T13:00:00.000Z",
                "blood_glucose_mg_per_dL_int": 140
              },
              {
                "datetime_string": "2024-04-25T13:30:00.000Z",
                "blood_glucose_mg_per_dL_int": 160
              },
              {
                "datetime_string": "2024-04-25T14:00:00.000Z",
                "blood_glucose_mg_per_dL_int": 180
              },
              {
                "datetime_string": "2024-04-25T14:30:00.000Z",
                "blood_glucose_mg_per_dL_int": 200
              },
              {
                "datetime_string": "2024-04-25T15:00:00.000Z",
                "blood_glucose_mg_per_dL_int": 190
              },
              {
                "datetime_string": "2024-04-25T15:30:00.000Z",
                "blood_glucose_mg_per_dL_int": 180
              },
              {
                "datetime_string": "2024-04-25T16:00:00.000Z",
                "blood_glucose_mg_per_dL_int": 170
              },
              {
                "datetime_string": "2024-04-25T16:30:00.000Z",
                "blood_glucose_mg_per_dL_int": 160
              }
            ]
          }
        }
      ]
    }
  }
}
```
