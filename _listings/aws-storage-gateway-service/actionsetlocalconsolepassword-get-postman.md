{
  "info": {
    "name": "AWS Storage Gateway Service API Set Local Console Password",
    "_postman_id": "3aa7ba8c-84c5-4943-a94a-853998a7a0dc",
    "description": "Sets the password for your VM local console.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Gateway",
      "item": [
        {
          "id": "1cb6a4f6-d2bb-43b7-b336-6b64728e5e08",
          "name": "activateGateway",
          "request": {
            "url": "http://example.com/api/?Action=ActivateGateway?ActivationKey=ActivationKey&GatewayName=GatewayName&GatewayRegion=GatewayRegion&GatewayTimezone=GatewayTimezone&GatewayType=GatewayType&MediumChangerType=MediumChangerType&TapeDriveType=TapeDriveType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Activates the gateway you previously deployed on your host."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bf58bc03-407b-494d-aa3e-88ce3d9b6b84"
            }
          ]
        },
        {
          "id": "eca6471b-215c-47bb-8695-b95bad1282d3",
          "name": "deleteGateway",
          "request": {
            "url": "http://example.com/api/?Action=DeleteGateway?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cc1db9d5-404e-4d84-a678-d4482148ed87"
            }
          ]
        },
        {
          "id": "43dd7143-205e-476b-837f-875a31829b59",
          "name": "describeGatewayInformation",
          "request": {
            "url": "http://example.com/api/?Action=DescribeGatewayInformation?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns metadata about a gateway such as its name, network interfaces, configured\n         time zone, and the state (whether the gateway is running or not)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "94663c99-b894-4277-8978-9e87cbb3fbfa"
            }
          ]
        },
        {
          "id": "022032b7-979b-40b9-9bf8-49839577a638",
          "name": "disableGateway",
          "request": {
            "url": "http://example.com/api/?Action=DisableGateway?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables a gateway when the gateway is no longer functioning."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b93bf677-48ea-4843-9d24-f0de52ed6463"
            }
          ]
        }
      ]
    },
    {
      "name": "Cache",
      "item": [
        {
          "id": "62626293-edf3-4e0e-aab2-343aae85230a",
          "name": "addCache",
          "request": {
            "url": "http://example.com/api/?Action=AddCache?DiskIds=DiskIds&GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Configures one or more gateway local disks as cache for a cached-volume gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3679edad-ed4b-4306-8e79-4a121b04c708"
            }
          ]
        },
        {
          "id": "d5b7d076-649a-4875-b09f-25c86a248058",
          "name": "describeCache",
          "request": {
            "url": "http://example.com/api/?Action=DescribeCache?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about the cache of a gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "954ab684-a350-43a9-a7c9-15515e7386ea"
            }
          ]
        },
        {
          "id": "93faecb1-aad1-4585-849e-406f75e3468e",
          "name": "resetCache",
          "request": {
            "url": "http://example.com/api/?Action=ResetCache?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets all cache disks that have encountered a error and makes the disks available\n         for reconfiguration as cache storage."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "98283260-2d56-42f6-bc2f-690aa42bce3c"
            }
          ]
        }
      ]
    },
    {
      "name": "Tags",
      "item": [
        {
          "id": "f651664b-b456-4824-8820-62dc8b11ee77",
          "name": "addTagsToResource",
          "request": {
            "url": "http://example.com/api/?Action=AddTagsToResource?ResourceARN=ResourceARN&Tags=Tags",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds one or more tags to the specified resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0b278748-6172-40dc-aaed-b3c7b30b275a"
            }
          ]
        },
        {
          "id": "6ebd1af6-eb1e-4c94-a029-6b9d6f6fb3d5",
          "name": "listTagsForResource",
          "request": {
            "url": "http://example.com/api/?Action=ListTagsForResource?Limit=Limit&Marker=Marker&ResourceARN=ResourceARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the tags that have been added to the specified resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "895e9a2e-380c-435a-aca5-09d2700ea239"
            }
          ]
        },
        {
          "id": "62139fc8-8025-4601-8b2c-6347a59d6dcc",
          "name": "removeTagsFromResource",
          "request": {
            "url": "http://example.com/api/?Action=RemoveTagsFromResource?ResourceARN=ResourceARN&TagKeys=TagKeys",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes one or more tags from the specified resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "43737b4e-125c-471a-8509-18ea1303a2b5"
            }
          ]
        }
      ]
    },
    {
      "name": "Upload Buffer",
      "item": [
        {
          "id": "b156721f-03a7-4c80-87b1-1bfcaf9427a0",
          "name": "addUploadBuffer",
          "request": {
            "url": "http://example.com/api/?Action=AddUploadBuffer?DiskIds=DiskIds&GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Configures one or more gateway local disks as upload buffer for a specified gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b9c70bd6-b931-4a9d-896a-240f032f5948"
            }
          ]
        },
        {
          "id": "3f3e0603-8e4c-4221-8ab0-775e95239f5e",
          "name": "describeUploadBuffer",
          "request": {
            "url": "http://example.com/api/?Action=DescribeUploadBuffer?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about the upload buffer of a gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8313f444-bb9b-4a44-a6ef-bbae27fa3bd3"
            }
          ]
        }
      ]
    },
    {
      "name": "Working Storage",
      "item": [
        {
          "id": "5786e40b-06f2-4bee-aa04-539b303d031a",
          "name": "addWorkingStorage",
          "request": {
            "url": "http://example.com/api/?Action=AddWorkingStorage?DiskIds=DiskIds&GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Configures one or more gateway local disks as working storage for a gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4a1e04e7-e237-4e6f-a09f-9c8416d01d1f"
            }
          ]
        },
        {
          "id": "80e214ba-d213-47fe-8980-478e41604308",
          "name": "describeWorkingStorage",
          "request": {
            "url": "http://example.com/api/?Action=DescribeWorkingStorage?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about the working storage of a gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c71f7ba0-e116-4f47-9a3d-3d82c6024f8d"
            }
          ]
        }
      ]
    },
    {
      "name": "Archival",
      "item": [
        {
          "id": "0be6857d-f006-4c51-863c-a2cc1de8cea7",
          "name": "cancelArchival",
          "request": {
            "url": "http://example.com/api/?Action=CancelArchival?GatewayARN=GatewayARN&TapeARN=TapeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels archiving of a virtual tape to the virtual tape shelf (VTS) after the\n         archiving process is initiated."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3df7f479-1b1e-4738-bce1-8aeceaf889fb"
            }
          ]
        }
      ]
    },
    {
      "name": "Retrieval",
      "item": [
        {
          "id": "01661003-f2dc-4bec-8881-f4f8021497d5",
          "name": "cancelRetrieval",
          "request": {
            "url": "http://example.com/api/?Action=CancelRetrieval?GatewayARN=GatewayARN&TapeARN=TapeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels retrieval of a virtual tape from the virtual tape shelf (VTS) to a gateway\n         after the retrieval process is initiated."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2b956521-687d-41ce-b01b-4a87cd743b2e"
            }
          ]
        }
      ]
    },
    {
      "name": "Cached SCSI Volume",
      "item": [
        {
          "id": "c646dbc2-67d5-419f-8072-4a00b963ec96",
          "name": "createCachediSCSIVolume",
          "request": {
            "url": "http://example.com/api/?Action=CreateCachediSCSIVolume?ClientToken=ClientToken&GatewayARN=GatewayARN&NetworkInterfaceId=NetworkInterfaceId&SnapshotId=SnapshotId&SourceVolumeARN=SourceVolumeARN&TargetName=TargetName&VolumeSizeInBytes=VolumeSizeInBytes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a cached volume on a specified cached gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cbd572e8-b8c7-438a-9c70-28178aca0516"
            }
          ]
        }
      ]
    },
    {
      "name": "NFS File Share",
      "item": [
        {
          "id": "a2e8eaa6-5b3d-4007-8747-b429a5436e63",
          "name": "createNFSFileShare",
          "request": {
            "url": "http://example.com/api/?Action=CreateNFSFileShare?ClientToken=ClientToken&DefaultStorageClass=DefaultStorageClass&GatewayARN=GatewayARN&KMSEncrypted=KMSEncrypted&KMSKey=KMSKey&LocationARN=LocationARN&NFSFileShareDefaults=NFSFileShareDefaults&Role=Role",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a file share on an existing file gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "13b510d2-b31f-4128-babe-2f06f6c8dd9f"
            }
          ]
        }
      ]
    },
    {
      "name": "Snapshots",
      "item": [
        {
          "id": "b9741b37-2638-401a-a30e-28d003a169b1",
          "name": "createSnapshot",
          "request": {
            "url": "http://example.com/api/?Action=CreateSnapshot?SnapshotDescription=SnapshotDescription&VolumeARN=VolumeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Initiates a snapshot of a volume."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5cbe3dc9-efc6-4321-bde2-1cc830decfe3"
            }
          ]
        },
        {
          "id": "0d448909-5022-40c4-8c5f-330db6862226",
          "name": "createSnapshotFromVolumeRecoveryPoint",
          "request": {
            "url": "http://example.com/api/?Action=CreateSnapshotFromVolumeRecoveryPoint?SnapshotDescription=SnapshotDescription&VolumeARN=VolumeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Initiates a snapshot of a gateway from a volume recovery point."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "126eed56-2205-4ec3-8cf3-7d52f7163157"
            }
          ]
        },
        {
          "id": "e40f12a3-61bb-4d90-8ad3-c2d0805b28d8",
          "name": "deleteSnapshotSchedule",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSnapshotSchedule?VolumeARN=VolumeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a snapshot of a volume."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4ba6af4f-7685-41b2-b1af-faa29d9026db"
            }
          ]
        },
        {
          "id": "2d7ebf66-f6cd-48b5-b9b8-4edfecb08885",
          "name": "describeSnapshotSchedule",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSnapshotSchedule?VolumeARN=VolumeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the snapshot schedule for the specified gateway volume."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9ae9b82a-d8fb-4f94-bdbf-c39247d14d9a"
            }
          ]
        }
      ]
    },
    {
      "name": "Stored SCSI Volume",
      "item": [
        {
          "id": "6448b92a-c80c-4ca2-909d-720301f80588",
          "name": "createStorediSCSIVolume",
          "request": {
            "url": "http://example.com/api/?Action=CreateStorediSCSIVolume?DiskId=DiskId&GatewayARN=GatewayARN&NetworkInterfaceId=NetworkInterfaceId&PreserveExistingData=PreserveExistingData&SnapshotId=SnapshotId&TargetName=TargetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a volume on a specified gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "34fa24b5-0ed7-42e7-82ce-b16aa565d316"
            }
          ]
        }
      ]
    },
    {
      "name": "Tapes",
      "item": [
        {
          "id": "8da31cf2-9ecd-4086-b7fb-3b956d4e4f4f",
          "name": "createTapes",
          "request": {
            "url": "http://example.com/api/?Action=CreateTapes?ClientToken=ClientToken&GatewayARN=GatewayARN&NumTapesToCreate=NumTapesToCreate&TapeBarcodePrefix=TapeBarcodePrefix&TapeSizeInBytes=TapeSizeInBytes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates one or more virtual tapes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "02337452-d418-43d3-a4e7-9e14af8f3510"
            }
          ]
        },
        {
          "id": "322cdef3-3773-4008-8b9a-7e0de789d972",
          "name": "deleteTape",
          "request": {
            "url": "http://example.com/api/?Action=DeleteTape?GatewayARN=GatewayARN&TapeARN=TapeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified virtual tape."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eed1f599-5b55-4e98-b94b-870eb8677382"
            }
          ]
        },
        {
          "id": "ff358705-1e60-447e-a9d8-ffc8c6a1f59e",
          "name": "deleteTapeArchive",
          "request": {
            "url": "http://example.com/api/?Action=DeleteTapeArchive?TapeARN=TapeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified virtual tape from the virtual tape shelf (VTS)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "421ff49d-c2c8-43fc-8af6-1734fb6ff5bd"
            }
          ]
        },
        {
          "id": "7b666a36-a028-49ae-b9a2-4c1cd1b37a59",
          "name": "describeTapes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeTapes?GatewayARN=GatewayARN&Limit=Limit&Marker=Marker&TapeARNs=TapeARNs",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a description of the specified Amazon Resource Name (ARN) of virtual tapes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c50b11a4-1526-4ac8-87d1-0c2367f5ec96"
            }
          ]
        },
        {
          "id": "8220108e-1b83-4e13-9f48-96b51e1739ca",
          "name": "listTapes",
          "request": {
            "url": "http://example.com/api/?Action=ListTapes?Limit=Limit&Marker=Marker&TapeARNs=TapeARNs",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists virtual tapes in your virtual tape library (VTL) and your virtual tape shelf\n         (VTS)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8dd0a535-7050-47f7-bfe0-1723a312a9f6"
            }
          ]
        },
        {
          "id": "52b1d36c-6a81-4892-ae48-ef821551005e",
          "name": "retrieveTapeArchive",
          "request": {
            "url": "http://example.com/api/?Action=RetrieveTapeArchive?GatewayARN=GatewayARN&TapeARN=TapeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves an archived virtual tape from the virtual tape shelf (VTS) to a\n         gateway-VTL."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6c178202-01c2-4cf6-a428-780e8a57c55b"
            }
          ]
        }
      ]
    },
    {
      "name": "Tape With Barcode",
      "item": [
        {
          "id": "48cb5afe-6c5d-4240-aa43-1ffe2d5e870a",
          "name": "createTapeWithBarcode",
          "request": {
            "url": "http://example.com/api/?Action=CreateTapeWithBarcode?GatewayARN=GatewayARN&TapeBarcode=TapeBarcode&TapeSizeInBytes=TapeSizeInBytes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a virtual tape by using your own barcode."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f9017e79-51cd-49ac-b15c-7ad0bc666b32"
            }
          ]
        }
      ]
    },
    {
      "name": "Bandwidth Rate Limit",
      "item": [
        {
          "id": "5656bc2a-be29-4f45-b2ca-0a114d5879a0",
          "name": "deleteBandwidthRateLimit",
          "request": {
            "url": "http://example.com/api/?Action=DeleteBandwidthRateLimit?BandwidthType=BandwidthType&GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the bandwidth rate limits of a gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ad25ba04-c75e-4163-9a4e-ad30f3558ad3"
            }
          ]
        },
        {
          "id": "320cd7cc-03b8-4bde-9ae4-c5ceb2d33398",
          "name": "describeBandwidthRateLimit",
          "request": {
            "url": "http://example.com/api/?Action=DescribeBandwidthRateLimit?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the bandwidth rate limits of a gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "63441d9d-fb2e-4dcf-94c6-3144a2206acc"
            }
          ]
        }
      ]
    },
    {
      "name": "Chap Credentials",
      "item": [
        {
          "id": "09069028-8c21-42f0-a509-c116d24c61e1",
          "name": "deleteChapCredentials",
          "request": {
            "url": "http://example.com/api/?Action=DeleteChapCredentials?InitiatorName=InitiatorName&TargetARN=TargetARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes Challenge-Handshake Authentication Protocol (CHAP) credentials for a\n         specified iSCSI target and initiator pair."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "285e646a-9606-4210-ae7c-b2a38aeecb2d"
            }
          ]
        },
        {
          "id": "c2fd81ba-efb2-4e30-82f0-81fe58eb18b1",
          "name": "describeChapCredentials",
          "request": {
            "url": "http://example.com/api/?Action=DescribeChapCredentials?TargetARN=TargetARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns an array of Challenge-Handshake Authentication Protocol (CHAP) credentials\n         information for a specified iSCSI target, one for each target-initiator pair."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6b2c1d40-a96c-4965-9aac-c5b21479f4e4"
            }
          ]
        }
      ]
    },
    {
      "name": "File Share",
      "item": [
        {
          "id": "7cd4193b-2c38-477d-b1bd-9d9288640adc",
          "name": "deleteFileShare",
          "request": {
            "url": "http://example.com/api/?Action=DeleteFileShare?FileShareARN=FileShareARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a file share from a file gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "35e187dd-5dac-42ec-bdba-0e616b04faab"
            }
          ]
        }
      ]
    },
    {
      "name": "Volumes",
      "item": [
        {
          "id": "f2f85892-58b8-4ca1-b37c-a72e4791a07f",
          "name": "deleteVolume",
          "request": {
            "url": "http://example.com/api/?Action=DeleteVolume?VolumeARN=VolumeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified gateway volume that you previously created using the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a448a94a-aaf4-41dc-844b-bf7bcf3313dc"
            }
          ]
        },
        {
          "id": "b2586941-a725-4e7b-bcc4-20c9d120da4f",
          "name": "listVolumes",
          "request": {
            "url": "http://example.com/api/?Action=ListVolumes?GatewayARN=GatewayARN&Limit=Limit&Marker=Marker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the iSCSI stored volumes of a gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2ea2fbdb-f4f4-4283-9aae-ad8f840c95b4"
            }
          ]
        }
      ]
    },
    {
      "name": "Cached SCSI Volumes",
      "item": [
        {
          "id": "607ccc35-2ffa-4172-99a9-2a12ee9cfc16",
          "name": "describeCachediSCSIVolumes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeCachediSCSIVolumes?VolumeARNs=VolumeARNs",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a description of the gateway volumes specified in the request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a57bdb12-8634-4fe6-b6f2-8723c9262c1a"
            }
          ]
        }
      ]
    },
    {
      "name": "Maintenance",
      "item": [
        {
          "id": "d00d520c-5f99-44fc-979a-0f82e3a6d0a7",
          "name": "describeMaintenanceStartTime",
          "request": {
            "url": "http://example.com/api/?Action=DescribeMaintenanceStartTime?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns your gateway's weekly maintenance start time including the day and time of\n         the week."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a3dee885-dc9a-48d2-b5eb-32c7d92cf8ce"
            }
          ]
        }
      ]
    },
    {
      "name": "NFS File Shares",
      "item": [
        {
          "id": "3d4c9c9c-c0d2-47bc-9268-1dac1e629299",
          "name": "describeNFSFileShares",
          "request": {
            "url": "http://example.com/api/?Action=DescribeNFSFileShares?FileShareARNList=FileShareARNList",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a description for one or more file shares from a file gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "430158ab-c651-4fa3-9e73-0515daef7f06"
            }
          ]
        }
      ]
    },
    {
      "name": "Stored SCSI Volumes",
      "item": [
        {
          "id": "6556fd7d-7ed3-4e43-ae3e-be364d69f29a",
          "name": "describeStorediSCSIVolumes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeStorediSCSIVolumes?VolumeARNs=VolumeARNs",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the description of the gateway volumes specified in the request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "716f4e8c-663b-411f-9413-bb7e616bb8c7"
            }
          ]
        }
      ]
    },
    {
      "name": "Tape Archives",
      "item": [
        {
          "id": "19c69746-c442-41df-8a51-ec2059010080",
          "name": "describeTapeArchives",
          "request": {
            "url": "http://example.com/api/?Action=DescribeTapeArchives?Limit=Limit&Marker=Marker&TapeARNs=TapeARNs",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a description of specified virtual tapes in the virtual tape shelf\n         (VTS)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ca470387-30f5-456e-b7c0-f151985628bf"
            }
          ]
        }
      ]
    },
    {
      "name": "Tape Recovery Points",
      "item": [
        {
          "id": "e4490f06-e52a-44d1-9b2c-a0a761c75ccd",
          "name": "describeTapeRecoveryPoints",
          "request": {
            "url": "http://example.com/api/?Action=DescribeTapeRecoveryPoints?GatewayARN=GatewayARN&Limit=Limit&Marker=Marker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of virtual tape recovery points that are available for the specified\n         gateway-VTL."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0dfd3aad-6acd-4ca3-8886-cba7f7d680f0"
            }
          ]
        }
      ]
    },
    {
      "name": "VTL Devices",
      "item": [
        {
          "id": "fa0b4a35-cb00-4930-8e78-eb9870ae84ce",
          "name": "describeVTLDevices",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVTLDevices?GatewayARN=GatewayARN&Limit=Limit&Marker=Marker&VTLDeviceARNs=VTLDeviceARNs",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a description of virtual tape library (VTL) devices for the specified\n         gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e6bfdfdc-2095-4b72-ab76-3d2a9756e3df"
            }
          ]
        }
      ]
    },
    {
      "name": "File Shares",
      "item": [
        {
          "id": "d1031e94-edb6-4f07-b03b-34ce6f77e4a1",
          "name": "listFileShares",
          "request": {
            "url": "http://example.com/api/?Action=ListFileShares?GatewayARN=GatewayARN&Limit=Limit&Marker=Marker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of the file shares for a specific file gateway, or the list of file shares that belong to the calling user account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "593b67fd-756f-4df3-8e92-cb4717a32169"
            }
          ]
        }
      ]
    },
    {
      "name": "Gateways",
      "item": [
        {
          "id": "70f8067b-8440-43f9-839e-b4e01b6cbbab",
          "name": "listGateways",
          "request": {
            "url": "http://example.com/api/?Action=ListGateways?Limit=Limit&Marker=Marker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists gateways owned by an AWS account in a region specified in the request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "10c42c25-51fa-4101-bd60-db141abc9468"
            }
          ]
        }
      ]
    },
    {
      "name": "Local Disks",
      "item": [
        {
          "id": "aecfe807-baf1-4dbc-9780-38b5b69fcb04",
          "name": "listLocalDisks",
          "request": {
            "url": "http://example.com/api/?Action=ListLocalDisks?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of the gateway's local disks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a6ae6192-dab6-4189-a3ef-838367e97761"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume Initiators",
      "item": [
        {
          "id": "b3fa5e06-5ad7-435f-b58a-694cdf900410",
          "name": "listVolumeInitiators",
          "request": {
            "url": "http://example.com/api/?Action=ListVolumeInitiators?VolumeARN=VolumeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists iSCSI initiators that are connected to a volume."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "584e57a3-dfb2-4657-9a4e-5c5a49d33682"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume Recovery",
      "item": [
        {
          "id": "c3fef882-28ee-4a79-ab78-08531c5cae14",
          "name": "listVolumeRecoveryPoints",
          "request": {
            "url": "http://example.com/api/?Action=ListVolumeRecoveryPoints?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the recovery points for a specified gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f4267c06-cf65-476d-9648-29647e1993d1"
            }
          ]
        }
      ]
    },
    {
      "name": "Tape Recovery",
      "item": [
        {
          "id": "1177793a-28db-440b-b579-ceb7434742a5",
          "name": "retrieveTapeRecoveryPoint",
          "request": {
            "url": "http://example.com/api/?Action=RetrieveTapeRecoveryPoint?GatewayARN=GatewayARN&TapeARN=TapeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the recovery point for the specified virtual tape."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "11cde66b-bf65-4a59-a5b5-249aa879a22b"
            }
          ]
        }
      ]
    },
    {
      "name": "Local Console Password",
      "item": [
        {
          "id": "2e54b00c-b0cc-4e7b-977c-ef074352c4bb",
          "name": "setLocalConsolePassword",
          "request": {
            "url": "http://example.com/api/?Action=SetLocalConsolePassword?GatewayARN=GatewayARN&LocalConsolePassword=LocalConsolePassword",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets the password for your VM local console."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e017c5ee-629d-404d-aecf-fbf7f8af5d07"
            }
          ]
        }
      ]
    }
  ]
}