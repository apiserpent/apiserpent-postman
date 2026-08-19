# API Serpent Postman Collection & OpenAPI Spec

Official API testing resources for [API Serpent](https://apiserpent.com/). Test our SERP API, Rank Tracking API, and Pixel Position API endpoints instantly in Postman or import the OpenAPI definition into your favorite API client.

## Quick Start with Postman

1. Download the [`apiserpent_postman_collection.json`](./apiserpent_postman_collection.json) file from this repository.
2. Open **Postman** and click **Import** in the top-left corner.
3. Drag and drop the downloaded JSON file.
4. Set your `API_KEY` collection variable to start making live search requests!

---

## Included Endpoints

| Endpoint | Method | Description |
| :--- | :--- | :--- |
| `/api/search` | `GET` | Fetch real-time search engine results (Google, Bing, Yahoo, DuckDuckGo). |
| `/api/rank` | `GET` | Check exact domain ranking position for specified keywords. |
| `/api/pixel` | `GET` | Retrieve pixel-level position placement data for search results. |

---

## Quick Curl Example

```bash
curl -X GET "https://apiserpent.com/api/search?q=postman+serp+api&engine=google" \
     -H "X-API-Key: YOUR_API_SERPENT_KEY"
```

---

## Documentation & Links

- [Official API Documentation](https://apiserpent.com/docs)
- [SERP API Overview](https://apiserpent.com/serp-api)
- [Get 10 Free API Calls](https://apiserpent.com/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
