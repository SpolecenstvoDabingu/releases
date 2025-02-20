# Release datas for website [SpolečenstvoDabingu](https://spolecenstvodabingu.github.io/webpage/)


## Data structure

```json
[
    {
        "name": "Series Name",
        "nameShort": "SN",
        "thumbnail": "URL to thumbnail",
        "banner": "URL to banner",
        "description": "Description for the whole series",
        "episodes": [
            {
                "season": 1,
                "episode": 1,
                "name": "Episode Name",
                "description": "Description for episode",
                "thumbnail": "URL to thumbnail",
                "banner": "URL to banner",
                "video": "URL to video",
                "timestamp": 0,
                "dubbers": [
                    {
                        "name": "Dubber name",
                        "character": "Character name"
                    }
                ]
            }            
            // another episode here
        ],
        "scenes": [
            {
                "season": 1,
                "episode": 1,
                "start": 0,     // start of scene in seconds
                "end": 100,     // end of scene in seconds
                "name": "Scene Name",
                "description": "Description for scene",
                "thumbnail": "URL to thumbnail",
                "banner": "URL to banner",
                "video": "URL to scene",
                "timestamp": 0,
                "dubbers": [
                    {
                        "name": "Dubber name",
                        "character": "Character name"
                    }
                ]
            }
            // another scene here
        ],
        "movies": [
            {
                "orderID": 1,
                "name": "Movie Name",
                "description": "Description for scene",
                "thumbnail": "URL to thumbnail",
                "banner": "URL to banner",
                "video": "URL to scene",
                "timestamp": 0,
                "dubbers": [
                    {
                        "name": "Dubber name",
                        "character": "Character name"
                    }
                ]
            }
            // another movie here
        ],
        "upcomming": {
            "episodes": [
                {
                    "season": 1,
                    "episode": 1,
                    "name": "Episode Name",
                    "description": "Description for episode",
                    "thumbnail": "URL to thumbnail",
                    "banner": "URL to banner",
                    "timestamp": 0,
                    "dubbers": [
                        {
                            "name": "Dubber name",
                            "character": "Character name"
                        }
                    ]
                }            
                // another episode here
            ],
            "movies": [
                {
                    "orderID": 1,
                    "name": "Movie Name",
                    "description": "Description for scene",
                    "thumbnail": "URL to thumbnail",
                    "banner": "URL to banner",
                    "timestamp": 0,
                    "dubbers": [
                        {
                            "name": "Dubber name",
                            "character": "Character name"
                        }
                    ]
                }
                // another movie here                
            ],
            "scenes": [
                {
                    "season": 1,
                    "episode": 1,
                    "start": 0,     // start of scene in seconds
                    "end": 100,     // end of scene in seconds
                    "name": "Scene Name",
                    "description": "Description for scene",
                    "thumbnail": "URL to thumbnail",
                    "banner": "URL to banner",
                    "timestamp": 0,
                    "dubbers": [
                        {
                            "name": "Dubber name",
                            "character": "Character name"
                        }
                    ]
                }
                // another scene here
            ]
        }
    }
    // another series here
]
```