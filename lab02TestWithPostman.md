{
	"info": {
		"_postman_id": "cf8766b5-9046-48a1-becf-f1c60c8e60f5",
		"name": "BMTTNC",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json",
		"_exporter_id": "40245430"
	},
	"item": [
		{
			"name": "lab-02",
			"item": [
				{
					"name": "caesar",
					"item": [
						{
							"name": "encrypt",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "raw",
									"raw": "{\r\n    \"plain_text\" : \"HUTECH\",\r\n    \"key\" : \"3\"\r\n\r\n}",
									"options": {
										"raw": {
											"language": "json"
										}
									}
								},
								"url": {
									"raw": "http://127.0.0.1:5000/api/caesar/encrypt",
									"protocol": "http",
									"host": [
										"127",
										"0",
										"0",
										"1"
									],
									"port": "5000",
									"path": [
										"api",
										"caesar",
										"encrypt"
									]
								}
							},
							"response": []
						},
						{
							"name": "decrypt",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "raw",
									"raw": "{\r\n    \"cipher_text\" : \"KXWHFK\",\r\n    \"key\" : \"3\"\r\n\r\n}",
									"options": {
										"raw": {
											"language": "json"
										}
									}
								},
								"url": {
									"raw": "http://127.0.0.1:5000/api/caesar/decrypt",
									"protocol": "http",
									"host": [
										"127",
										"0",
										"0",
										"1"
									],
									"port": "5000",
									"path": [
										"api",
										"caesar",
										"decrypt"
									]
								}
							},
							"response": []
						}
					]
				},
				{
					"name": "vigenere",
					"item": [
						{
							"name": "encrypt",
							"request": {
								"method": "POST",
								"header": [
									{
										"key": "Content-Type",
										"value": "application/json",
										"type": "text"
									}
								],
								"body": {
									"mode": "raw",
									"raw": "{\r\n    \"plain_text\" : \"HUTECH\",\r\n    \"key\" : \"ABC\"\r\n}",
									"options": {
										"raw": {
											"language": "json"
										}
									}
								},
								"url": {
									"raw": "http://127.0.0.1:5000/api/vigenere/encrypt",
									"protocol": "http",
									"host": [
										"127",
										"0",
										"0",
										"1"
									],
									"port": "5000",
									"path": [
										"api",
										"vigenere",
										"encrypt"
									]
								}
							},
							"response": []
						},
						{
							"name": "decrypt",
							"request": {
								"method": "POST",
								"header": [
									{
										"key": "Content-Type",
										"value": "application/json",
										"type": "text"
									}
								],
								"body": {
									"mode": "raw",
									"raw": "{\r\n    \"cipher_text\" : \"HVVEDJ\",\r\n    \"key\" : \"ABC\"\r\n}"
								},
								"url": {
									"raw": "http://127.0.0.1:5000/api/vigenere/decrypt",
									"protocol": "http",
									"host": [
										"127",
										"0",
										"0",
										"1"
									],
									"port": "5000",
									"path": [
										"api",
										"vigenere",
										"decrypt"
									]
								}
							},
							"response": []
						}
					]
				},
				{
					"name": "Rail Fence",
					"item": [
						{
							"name": "encrypt",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "raw",
									"raw": "{\r\n  \"plain_text\": \"HUTECHUNIVERSITY\",\r\n  \"key\": \"3\"\r\n}\r\n",
									"options": {
										"raw": {
											"language": "json"
										}
									}
								},
								"url": {
									"raw": "http://127.0.0.1:5000/api/railfence/encrypt",
									"protocol": "http",
									"host": [
										"127",
										"0",
										"0",
										"1"
									],
									"port": "5000",
									"path": [
										"api",
										"railfence",
										"encrypt"
									]
								}
							},
							"response": []
						},
						{
							"name": "decrypt",
							"request": {
								"method": "POST",
								"header": [],
								"url": {
									"raw": "http://127.0.0.1:5000/api/railfence/encrypt",
									"protocol": "http",
									"host": [
										"127",
										"0",
										"0",
										"1"
									],
									"port": "5000",
									"path": [
										"api",
										"railfence",
										"encrypt"
									]
								}
							},
							"response": []
						}
					]
				},
				{
					"name": "Playfair",
					"item": [
						{
							"name": "creatematrix",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "raw",
									"raw": "{\r\n  \"plain_text\": \"HOMNAYHANHDONG\",\r\n  \"key\": \"MONARCHY\"\r\n}\r\n",
									"options": {
										"raw": {
											"language": "json"
										}
									}
								},
								"url": {
									"raw": "http://127.0.0.1:5000/api/playfair/creatematrix",
									"protocol": "http",
									"host": [
										"127",
										"0",
										"0",
										"1"
									],
									"port": "5000",
									"path": [
										"api",
										"playfair",
										"creatematrix"
									]
								}
							},
							"response": []
						},
						{
							"name": "decrypt",
							"request": {
								"method": "POST",
								"header": [],
								"url": {
									"raw": "http://127.0.0.1:5000/api/railfence/encrypt",
									"protocol": "http",
									"host": [
										"127",
										"0",
										"0",
										"1"
									],
									"port": "5000",
									"path": [
										"api",
										"railfence",
										"encrypt"
									]
								}
							},
							"response": []
						},
						{
							"name": "encrypt",
							"request": {
								"method": "POST",
								"header": [],
								"url": {
									"raw": "http://127.0.0.1:5000/api/playfair/encrypt",
									"protocol": "http",
									"host": [
										"127",
										"0",
										"0",
										"1"
									],
									"port": "5000",
									"path": [
										"api",
										"playfair",
										"encrypt"
									]
								}
							},
							"response": []
						}
					]
				},
				{
					"name": "Transposition",
					"item": [
						{
							"name": "encrypt Copy",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "raw",
									"raw": "{\r\n    \"plain_text\" : \"HUTECH\",\r\n    \"key\" : \"3\"\r\n\r\n}",
									"options": {
										"raw": {
											"language": "json"
										}
									}
								},
								"url": {
									"raw": "http://127.0.0.1:5000/api/caesar/encrypt",
									"protocol": "http",
									"host": [
										"127",
										"0",
										"0",
										"1"
									],
									"port": "5000",
									"path": [
										"api",
										"caesar",
										"encrypt"
									]
								}
							},
							"response": []
						},
						{
							"name": "decrypt Copy",
							"request": {
								"method": "POST",
								"header": [],
								"body": {
									"mode": "raw",
									"raw": "{\r\n    \"cipher_text\" : \"HEUCTH\",\r\n    \"key\" : \"3\"\r\n\r\n}",
									"options": {
										"raw": {
											"language": "json"
										}
									}
								},
								"url": {
									"raw": "http://127.0.0.1:5000/api/transposition/decrypt",
									"protocol": "http",
									"host": [
										"127",
										"0",
										"0",
										"1"
									],
									"port": "5000",
									"path": [
										"api",
										"transposition",
										"decrypt"
									]
								}
							},
							"response": []
						}
					]
				}
			]
		}
	]
}