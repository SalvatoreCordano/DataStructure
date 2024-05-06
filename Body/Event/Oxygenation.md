# Oxygenation with data granular

Dataset: oxygenation Event - Physical Health

Data: "saturation_percentage_int" "vo2_mL_per_min_per_kg_int"

Data Sources: polar

## Frame dataset

![326365856-ae3cd921-06e2-4b8e-8764-a9572a776208](https://github.com/SalvatoreCordano/DataStructure/assets/147050219/21bbb51e-3279-4a67-8645-681cd10e0ddc)


```Json
{
  "client_uuid": "demoClientUUID",
  "user_id": "demoUserId",
  "version": 2,
  "document_version": 1,
  "auto_detected": false,
  "data_structure": "oxygenation_event",
  "body_health": {
    "events": {
      "oxygenation_event": [
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
          "oxygenation": {
            "saturation_avg_percentage_int": 0,
            "saturation_granular_data_array": [
              {
                "datetime_string": "2023-12-29T21:07:14.402999Z",
                "interval_duration_seconds_float": 0,
                "saturation_percentage_int": 0
              }
            ],
            "vo2max_mL_per_min_per_kg_int": 0,
            "vo2_granular_data_array": [
              {
                "datetime_string": "2023-12-29T21:07:14.402999Z",
                "interval_duration_seconds_float": 0,
                "vo2_mL_per_min_per_kg_int": 0
              }
            ]
          }
        }
      ]
    }
  }
}
```
