# Breathing with Sleep Health

Dataset: Sleep Summary -Sleep Health

Data: Breathing

## Frame

```Json
{
    "breathing": {
        "breaths_minimum_per_min_int": 12,
        "breaths_avg_per_min_int": 16,
        "breaths_maximum_per_min_int": 20,
        "breathing_granular_data_array": [
            {
                "datetime_string": "2023-12-28T22:00:00.000Z",
                "breaths_per_min_int": 15
            },
            {
                "datetime_string": "2023-12-28T22:30:00.000Z",
                "breaths_per_min_int": 16
            },
            {
                "datetime_string": "2023-12-28T23:00:00.000Z",
                "breaths_per_min_int": 17
            },
            {
                "datetime_string": "2023-12-28T23:30:00.000Z",
                "breaths_per_min_int": 16
            },
            {
                "datetime_string": "2023-12-29T00:00:00.000Z",
                "breaths_per_min_int": 15
            },
            {
                "datetime_string": "2023-12-29T00:30:00.000Z",
                "breaths_per_min_int": 14
            },
            {
                "datetime_string": "2023-12-29T01:00:00.000Z",
                "breaths_per_min_int": 13
            }
        ],
        "snoring_events_count_int": 5,
        "snoring_duration_total_seconds_int": 600,
        "snoring_granular_data_array": [
            {
                "datetime_string": "2023-12-28T23:15:00.000Z",
                "interval_duration_seconds_float": 120.0,
                "snoring_events_count_int": 1
            },
            {
                "datetime_string": "2023-12-29T00:45:00.000Z",
                "interval_duration_seconds_float": 180.0,
                "snoring_events_count_int": 2
            },
            {
                "datetime_string": "2023-12-29T01:30:00.000Z",
                "interval_duration_seconds_float": 300.0,
                "snoring_events_count_int": 2
            }
        ],
        "saturation_avg_percentage_int": 97,
        "saturation_minimum_percentage_int": 95,
        "saturation_maximum_percentage_int": 99,
        "saturation_granular_data_array": [
            {
                "datetime_string": "2023-12-28T22:00:00.000Z",
                "interval_duration_seconds_float_number": 60.0,
                "saturation_percentage_int": 97
            },
            {
                "datetime_string": "2023-12-28T22:30:00.000Z",
                "interval_duration_seconds_float_number": 60.0,
                "saturation_percentage_int": 98
            },
            {
                "datetime_string": "2023-12-28T23:00:00.000Z",
                "interval_duration_seconds_float_number": 60.0,
                "saturation_percentage_int": 97
            },
            {
                "datetime_string": "2023-12-28T23:30:00.000Z",
                "interval_duration_seconds_float_number": 60.0,
                "saturation_percentage_int": 96
            },
            {
                "datetime_string": "2023-12-29T00:00:00.000Z",
                "interval_duration_seconds_float_number": 60.0,
                "saturation_percentage_int": 95
            },
            {
                "datetime_string": "2023-12-29T00:30:00.000Z",
                "interval_duration_seconds_float_number": 60.0,
                "saturation_percentage_int": 96
            },
            {
                "datetime_string": "2023-12-29T01:00:00.000Z",
                "interval_duration_seconds_float_number": 60.0,
                "saturation_percentage_int": 97
            }
        ]
    }
}
```