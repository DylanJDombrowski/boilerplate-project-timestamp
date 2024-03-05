# Timestamp Microservice


### Documentation for Date Conversion API

```markdown
# Date Conversion API Documentation

This API endpoint converts dates to Unix timestamps and UTC strings.

## Endpoints

- `GET /api/:date?`: Converts the given date string or Unix timestamp to both Unix timestamp and UTC string.
- If no date is provided, the current time is used.

## Response

The response is a JSON object containing the following keys:

- `unix`: The Unix timestamp of the input date in milliseconds.
- `utc`: The UTC string of the input date in the format `Thu, 01 Jan 1970 00:00:00 GMT`.

### Example Request & Response

```plaintext
GET /api/1451001600000

