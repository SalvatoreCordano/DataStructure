# Stress with data granular

Dataset: Stress Event - Physical Health

Data: "distance"

Data Sources: Garmin

## Frame dataset

```Json
{
  "client_uuid": "demoClientUUID",
  "user_id": "demoUserId",
  "version": 2,
  "document_version": 1,
  "auto_detected": false,
  "data_structure": "stress_event",
  "physical_health": {
    "events": {
      "stress_event": [
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
          "stress": {
            "stress_at_rest_duration_seconds_int": 0,
            "stress_duration_seconds_int": 0,
            "low_stress_duration_seconds_int": 0,
            "medium_stress_duration_seconds_int": 0,
            "high_stress_duration_seconds_int": 0,
            "tss_granular_data_array": [
              {
                "datetime_string": "2023-12-29T21:07:14.402999Z",
                "interval_duration_seconds_float": 0,
                "tss_score_int": 0
              }
            ],
            "stress_avg_level_int": 0,
            "stress_maximum_level_int": 0
          }
        }
      ]
    }
  }
}
```
