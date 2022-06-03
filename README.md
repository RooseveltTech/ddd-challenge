# Devs, Drinks, and Data Challenge

Given a list of user phone numbers, pre-approve which users are eligible for loans on **December 1, 2021** based on the given decisioning criteria.

### Input data

The `phone_numbers.txt` file contains a newline-delimited list of phone numbers. These phone numbers are known to be associated with users in the `pngmedemo` organization.

### Decisioning criteria

Users should not be approved for a loan if:

1. The user has one or more defaulted loans in the past 90 days (relative to **December 1, 2021**).
1. The user has applied for more than 3 loans in the past 90 days (relative to **December 1, 2021**).

## Acceptance criteria

Indicate whether or not each phone number should be approved for a loan based on the above decisioning criteria. For example:

```csv
phone_number, is_approved
254789012345, true
2347014328765, false
...
```

## Resources

1. Pngme Dashboard ([admin.pngme.com](https://admin.pngme.com/))
1. [API Documentation](https://developers.api.pngme.com/reference/getting-started-with-your-api)
