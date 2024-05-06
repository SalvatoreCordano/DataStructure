# Oxygenation with data granular

Dataset: Oxygenation Event - Body Health

Data: "Oxygenation"

Data Sources: Apple Health

## Frame dataset

![descarga (11)](https://github.com/SalvatoreCordano/DataStructure/assets/147050219/ae3cd921-06e2-4b8e-8764-a9572a776208)

```Json
{
  "version": 2,
  "data_structure": "oxygenation_event",
  "client_uuid": "b10d3087-66f2-4f0c-9ead-63ee38c4f5e6",
  "user_id": "65eac303acf8df084a8a012c",
  "body_health": {
    "events": {
      "oxygenation_event": [
        {
          "metadata": {
            "datetime_string": "2024-03-04T20:05:09.961000+02:00",
            "user_id_string": "65eac303acf8df084a8a012c",
            "sources_of_data_array": [
              "Apple Health"
            ],
            "was_the_user_under_physical_activity_bool": false
          },
          "oxygenation": {
            "saturation_avg_percentage_int": 93,
            "saturation_granular_data_array": [
              {
                "saturation_percentage_int": 93,
                "datetime_string": "2024-03-04 20:05:09.961000+02:00",
                "interval_duration_seconds_float": null
              },
              {
                "saturation_percentage_int": 93,
                "datetime_string": "2024-03-04 20:35:10.837000+02:00",
                "interval_duration_seconds_float": null
              }
            ],
            "vo2max_mL_per_min_per_kg_int": null,
            "vo2_granular_data_array": []
          },
          "non_structured_data_array": []
        }
      ]
    }
  }
```
