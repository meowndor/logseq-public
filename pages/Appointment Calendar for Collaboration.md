- # Data Structure
- ```json
  {
    "name": "Your Name",
    "ID": "Your ID Number",
    "Semester" : ""
    "calendar": {
      "Class Schedule": {
        "Hydrology": {
          "code" : "TSH41147"
          "days": {
            "Monday": [
              {
                "start": "09:00",
                "end": "10:30",
                "tags": ["Introduction"],
                "description": "Introduction to Hydrology"
              },
              {
                "start": "13:00",
                "end": "14:30",
                "tags": ["Applications"],
                "description": "Applications of Hydrology in Environmental Engineering"
              }
            ],
            "Wednesday": {
              "start": "13:00",
              "end": "14:30"
            },
            "Friday": {
              "start": "10:00",
              "end": "12:00"
            }
          },
          "tags": ["Water Resources", "Environmental Engineering"]
        },
        "Geotechnic": {
          "days": {
            "Tuesday": {
              "start": "11:00",
              "end": "12:30"
            },
            "Thursday": {
              "start": "10:00",
              "end": "11:30"
            }
          },
          "tags": ["Soil Mechanics", "Foundation Engineering"],
          "practicum": "Sondir Test - Geotechnic"
        },
        "Analysis Structure": {
          "days": {
            "Monday": {
              "start": "11:00",
              "end": "12:30"
            },
            "Wednesday": {
              "start": "09:00",
              "end": "10:30"
            }
          },
          "tags": ["Structural Analysis", "Finite Element Method"]
        }
      },
      "Practicum Schedule": {
        "Sondir Test - Geotechnic": {
          "course": "Geotechnic",
          "days": {
            "Friday": {
              "start": "14:00",
              "end": "16:00"
            }
          },
          "tags": ["Preparation", "Testing"]
        }
      }
    }
  }
  
  ```