Service /service/call

{
  "service": "Wiki",
  "version": "0.0.1",
  "path": "/findarticles",
  "method": "post",
  "data": {
    "focus": {
      "offsets": [
        {
          "from": 0,
          "length": 6
        }
      ]
    },
    "context": {
      "text": "Germany",
      "source": "string",
      "lang": "string",
      "availabletypes": [
        "string"
      ],
      "annotations": [
        {
          "type": "string",
          "doffset": {
            "offsets": [
              {
                "from": 0,
                "length": 0
              }
            ]
          },
          "properties": {},
          "analyzer": "string"
        }
      ]
    }
  }
}


NLP /find/entities


{
  "text": "text Germany has a Mercedes",
  "source": "string",
  "lang": "string",
  "availabletypes": [
    "string"
  ],
  "annotations": [
  ]
}
