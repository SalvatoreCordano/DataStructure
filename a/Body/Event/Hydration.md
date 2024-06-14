# Hydration with data granular

Dataset: Hydratation Event - Physical Health

Data: "hydration_level_percentage_int"

Data Sources: Polar

## Frame dataset

![descarga (25)](https://github.com/SalvatoreCordano/DataStructure/assets/147050219/f8abe53c-ddaa-440c-a4a2-eb9e9f6f3522)


```Json
{
  "client_uuid": "demoClientUUID",
  "user_id": "demoUserId",
  "version": 2,
  "document_version": 1,
  "auto_detected": false,
  "data_structure": "hydration_event",
  "body_health": {
    "events": {
      "hydration_event": [
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
          "hydration": {
            "water_total_consumption_mL_int": 0,
            "hydration_amount_granular_data_array": [
              {
                "datetime_string": "2023-12-29T21:07:14.402999Z",
                "interval_duration_seconds_float": 0,
                "hydration_amount_mL_int": 0
              }
            ],
            "hydration_level_granular_data_array": [
              {
                "datetime_string": "2024-04-25T12:01:00Z",
                "interval_duration_seconds_float": 0.0,
                "hydration_level_percentage_int": 60
              },
              {
                "datetime_string": "2024-04-25T12:31:00Z",
                "interval_duration_seconds_float": 1800.0,
                "hydration_level_percentage_int": 59
              },
              {
                "datetime_string": "2024-04-25T13:01:00Z",
                "interval_duration_seconds_float": 1800.0,
                "hydration_level_percentage_int": 71
              },
              {
                "datetime_string": "2024-04-25T13:31:00Z",
                "interval_duration_seconds_float": 1800.0,
                "hydration_level_percentage_int": 68
              },
              {
                "datetime_string": "2024-04-25T14:01:00Z",
                "interval_duration_seconds_float": 1800.0,
                "hydration_level_percentage_int": 65
              }
            ]
          }
        }
      ]
    }
  }
}
```
