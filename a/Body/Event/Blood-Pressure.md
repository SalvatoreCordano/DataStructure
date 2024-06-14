# Blood Pressure with data granular

Dataset: Blood Pressure Event - Physical Health

Data: "diastolic_mmHg_int" "systolic_mmHg_int":

Data Sources: Garmin

## Frame dataset

![descarga (24)](https://github.com/SalvatoreCordano/DataStructure/assets/147050219/7f42dfee-f965-4b11-ac1f-2b5e60e79395)


```Json
{
  "client_uuid": "demoClientUUID",
  "user_id": "demoUserId",
  "version": 2,
  "document_version": 1,
  "auto_detected": false,
  "data_structure": "blood_pressure_event",
  "body_health": {
    "events": {
      "blood_pressure_event": [
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
          "blood_pressure": {
            "blood_pressure_avg_object": {
              "systolic_mmHg_int": 0,
              "diastolic_mmHg_int": 0
            },
            "blood_pressure_granular_data_array": [
              {
                "datetime_string": "2023-12-29T21:07:14.402999Z",
                "systolic_mmHg_int": 0,
                "diastolic_mmHg_int": 0
              }
            ]
          }
        }
      ]
    }
  }
}
```
