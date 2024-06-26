# Heart Rate with Sleep Health

Dataset: Sleep Summary -Sleep Health

Data: Heart Rate

## Frame

```Json
{
    "heart_rate": {
        "hr_maximum_bpm_int": 130,
        "hr_minimum_bpm_int": 50,
        "hr_avg_bpm_int": 75,
        "hr_resting_bpm_int": 60,
        "hr_basal_bpm_int": 55,
        "hr_granular_data_array": [
            {
                "datetime_string": "2023-12-28T22:30:00.000Z",
                "hr_bpm_int": 62
            },
            {
                "datetime_string": "2023-12-28T23:00:00.000Z",
                "hr_bpm_int": 60
            },
            {
                "datetime_string": "2023-12-29T00:00:00.000Z",
                "hr_bpm_int": 58
            }
        ],
        "hrv_avg_rmssd_float": 50.5,
        "hrv_avg_sdnn_float": 75.3,
        "hrv_sdnn_granular_data_array": [
            {
                "datetime_string": "2023-12-28T22:30:00.000Z",
                "hrv_sdnn_float": 70.0
            },
            {
                "datetime_string": "2023-12-28T23:00:00.000Z",
                "hrv_sdnn_float": 72.5
            },
            {
                "datetime_string": "2023-12-29T00:00:00.000Z",
                "hrv_sdnn_float": 73.2
            }
        ],
        "hrv_rmssd_granular_data_array": [
            {
                "datetime_string": "2023-12-28T22:30:00.000Z",
                "hrv_rmssd_float": 48.5
            },
            {
                "datetime_string": "2023-12-28T23:00:00.000Z",
                "hrv_rmssd_float": 49.8
            },
            {
                "datetime_string": "2023-12-29T00:00:00.000Z",
                "hrv_rmssd_float": 50.2
            }
        ]
    }
}
```