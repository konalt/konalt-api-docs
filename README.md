# Konalt API Docs
---
### API:deepai

| Endpoint | Method | Description | Body |
| --------------- | ------ | ----------------- | ----- |
| complete | POST | Autocomplete text with DeepAI's model. | text: string |

### API:discordbutton

| Endpoint | Method | Description | Body |
| --------------- | ------ | ----------------- | ----- |
| press | POST | Press THE BUTTON. | N/A |
| __forcepress | GET | Press THE BUTTON forcibly. | N/A |
| data | GET | Get button data. | N/A |

### API:generic

* Note: "generic" endpoints do not have a namespace.

| Endpoint | Method | Description | Body |
| --------------- | ------ | ----------------- | ----- |
| ip | GET | Get external IP. | N/A |
| time | GET | Get current server time. | N/A |
| cah | GET | Get a random CAH combo. | N/A |
| cah_white | GET | Get a random CAH white card. | N/A |

### API:xi

| Endpoint | Method | Description | Body |
| --------------- | ------ | ----------------- | ----- |
| upload_xi | POST | Uploads xi js file. Made for h*llow a while ago | xifile: file |

### API:cc

| Endpoint | Method | Description | Body |
| --------------- | ------ | ----------------- | ----- |
| upload_bg_image | POST | Upload a CCLive background. | bgImage: file |
| weather | GET | Get CCLive weather. | N/A |
| seanfocal | GET | Get CCLive seanfocal. | N/A |
| mistake | GET | Get CCLive common mistake. | N/A |
| settings | GET | Get current CCLive settings. | N/A |
| next_period | GET | Get next CCLive period. | N/A |
| time | GET | Clone of API:generic/time. | N/A |
| live_sync_data | GET | Clone of API:cc/settings. | N/A |
| settings_default | GET | Get default CCLive settings. | N/A |
| forcerefresh | GET | Get force refresh. | N/A |
| setforcerefresh/$set | GET | Set force refresh to $set. | N/A |
| changelivesettings | POST | Set CCLive settings | settings: object |
| upload_news_image | POST | Upload a CCLive news image. | newsImage: file |


### API:analytics

| Endpoint | Method | Description | Body |
| --------------- | ------ | ----------------- | ----- |
| requests | POST | Get logged requests. | name: string, pass: string |

### API:rmv

* Deprecated, use flaps watchparties instead
