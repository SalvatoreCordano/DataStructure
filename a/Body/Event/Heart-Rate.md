# Heart Rate with data granular

Dataset: Heart Rate Event - Body Health

Data: "Heart Rate"

Data Sources: Apple Health

## Frame dataset
![descarga (22)](https://github.com/SalvatoreCordano/DataStructure/assets/147050219/732aec9b-f1e5-44b6-9710-09dd7705999a)


```Json
{
  "version": 2,
  "data_structure": "heart_rate_event",
  "client_uuid": "0c32421f-6330-433d-a999-4ac1f4f8add5",
  "user_id": "6626b907fd3b48b1cdff0c9b",
  "document_version": 1,
  "auto_detected": false,
  "body_health": {
    "events": {
      "heart_rate_event": [
        {
          "metadata": {
            "datetime_string": "2024-04-09T10:03:38.483000-07:00",
            "user_id_string": "6626b907fd3b48b1cdff0c9b",
            "sources_of_data_array": [
              "Apple Health"
            ],
            "was_the_user_under_physical_activity_bool": false
          },
          "heart_rate": {
            "hr_maximum_bpm_int": 83,
            "hr_minimum_bpm_int": 60,
            "hr_avg_bpm_int": 71,
            "hr_resting_bpm_int": null,
            "hr_granular_data_array": [
              {
                "hr_bpm_int": 75,
                "datetime_string": "2024-04-09T10:03:38.483-07:00"
              },
              {
                "hr_bpm_int": 80,
                "datetime_string": "2024-04-09T10:04:54.983-07:00"
              },
              {
                "hr_bpm_int": 67,
                "datetime_string": "2024-04-09T10:12:47.483-07:00"
              },
              {
                "hr_bpm_int": 68,
                "datetime_string": "2024-04-09T10:18:30.108-07:00"
              },
              {
                "hr_bpm_int": 60,
                "datetime_string": "2024-04-09T10:22:49.233-07:00"
              },
              {
                "hr_bpm_int": 65,
                "datetime_string": "2024-04-09T10:27:31.358-07:00"
              },
              {
                "hr_bpm_int": 64,
                "datetime_string": "2024-04-09T10:29:25.858-07:00"
              },
              {
                "hr_bpm_int": 82,
                "datetime_string": "2024-04-09T10:37:43.144-07:00"
              },
              {
                "hr_bpm_int": 70,
                "datetime_string": "2024-04-09T10:38:07.358-07:00"
              },
              {
                "hr_bpm_int": 78,
                "datetime_string": "2024-04-09T10:41:32.608-07:00"
              },
              {
                "hr_bpm_int": 66,
                "datetime_string": "2024-04-09T10:46:11.608-07:00"
              },
              {
                "hr_bpm_int": 83,
                "datetime_string": "2024-04-09T10:52:49.108-07:00"
              },
              {
                "hr_bpm_int": 77,
                "datetime_string": "2024-04-09T10:58:11.983-07:00"
              }
            ],
            "hrv_avg_rmssd_float": null,
            "hrv_avg_sdnn_float": null,
            "hrv_sdnn_granular_data_array": [],
            "hrv_rmssd_granular_data_array": []
          },
          "non_structured_data_array": []
        }
      ]
    }
  }
},
```
