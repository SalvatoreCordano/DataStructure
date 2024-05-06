![descarga (28)](https://github.com/SalvatoreCordano/DataStructure/assets/147050219/6cc1b9f8-a4dc-4646-928c-ab94395e2d4d)![descarga (27)](https://github.com/SalvatoreCordano/DataStructure/assets/147050219/92556a7d-1792-44e8-abff-3146178b1fd1)# Oxygenation with data granular

Dataset: Oxygenation Event - Physical Health

Data: "distance"

Data Sources: Garmin

## Frame dataset

![descarga (28)](https://github.com/SalvatoreCordano/DataStructure/assets/147050219/6f175d7d-ac4c-44bb-940b-da9ac5e76a7e)

```Json
{
  "client_uuid": "demoClientUUID",
  "user_id": "demoUserId",
  "version": 2,
  "document_version": 1,
  "auto_detected": false,
  "data_structure": "oxygenation_event",
  "physical_health": {
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
                "interval_duration_seconds_float": 360.0,
                "vo2_mL_per_min_per_kg_int": 41
              },
              {
                "datetime_string": "2023-12-29T21:13:14.402999Z",
                "interval_duration_seconds_float": 360.0,
                "vo2_mL_per_min_per_kg_int": 35
              },
              {
                "datetime_string": "2023-12-29T21:19:14.402999Z",
                "interval_duration_seconds_float": 360.0,
                "vo2_mL_per_min_per_kg_int": 49
              },
              {
                "datetime_string": "2023-12-29T21:25:14.402999Z",
                "interval_duration_seconds_float": 360.0,
                "vo2_mL_per_min_per_kg_int": 30
              },
              {
                "datetime_string": "2023-12-29T21:31:14.402999Z",
                "interval_duration_seconds_float": 360.0,
                "vo2_mL_per_min_per_kg_int": 22
              },
              {
                "datetime_string": "2023-12-29T21:37:14.402999Z",
                "interval_duration_seconds_float": 360.0,
                "vo2_mL_per_min_per_kg_int": 17
              },
              {
                "datetime_string": "2023-12-29T21:43:14.402999Z",
                "interval_duration_seconds_float": 360.0,
                "vo2_mL_per_min_per_kg_int": 19
              },
              {
                "datetime_string": "2023-12-29T21:49:14.402999Z",
                "interval_duration_seconds_float": 360.0,
                "vo2_mL_per_min_per_kg_int": 49
              },
              {
                "datetime_string": "2023-12-29T21:55:14.402999Z",
                "interval_duration_seconds_float": 360.0,
                "vo2_mL_per_min_per_kg_int": 35
              },
              {
                "datetime_string": "2023-12-29T22:01:14.402999Z",
                "interval_duration_seconds_float": 360.0,
                "vo2_mL_per_min_per_kg_int": 45
              }
            ]
          }
        }
      ]
    }
  }
}
```
