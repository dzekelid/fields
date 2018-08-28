{
  "info": {
    "name": "National Crime Victimization Survey (NCVS) API Get Household Fields",
    "_postman_id": "561772d6-3335-4cc3-8a6e-61ec176dd58b",
    "description": "Returns a description of the fields/columns used returned in the household data sets.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Folder",
      "item": [
        {
          "id": "c6ab043b-8faa-445c-94b8-7304e2b456f1",
          "name": "getV2",
          "request": {
            "url": "http://www.bjs.gov/bjs/ncvs/v2/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of available datasets and data types they are available in."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9c997546-5759-4db8-a96a-8800b3efd3c8"
            }
          ]
        }
      ]
    },
    {
      "name": "Household",
      "item": [
        {
          "id": "2c6327b2-05db-420a-af7a-efec0881820f",
          "name": "getV2HouseholdFields",
          "request": {
            "url": "http://www.bjs.gov/bjs/ncvs/v2/household/fields/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a description of the fields/columns used returned in the household data sets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "afa07030-abf3-4f94-be72-64ee6a4b2668"
            }
          ]
        }
      ]
    }
  ]
}