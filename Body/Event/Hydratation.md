# Hydratation with data granular

Dataset: Hydratation Event - Physical Health

Data: "hydration_level_percentage_int"

Data Sources: Polar

## Frame dataset

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
                "datetime_string": "2023-12-29T21:07:14.402999Z",
                "interval_duration_seconds_float": 0,
                "hydration_level_percentage_int": 0
              }
            ]
          }
        }
      ]
    }
  }
}
```
