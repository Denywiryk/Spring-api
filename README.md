# Spring-api  

## Feature Four

_Greeting a User by choosing a greeting message from a predefined set of messages, **based on the time of the day**._

**Requesting a greeting message early in the morning**

```
When a User with the name Joe request a greeting message
And the time is early in the morning
Then the system will reply with a customized message that says:
"Good morning, Joe! The sun is high and shining!"
```

**List of predefined messages based on the time**

- **Morning (from 7 AM to 11 AM)** :sunny:
    - `Good morning, {User}! The sun is high and shining!`
    - `Hey {User}, nice to see you here!`
    - `{User} welcome back!`
    - `Have a splendid day {User}.`
- **The rest of the day (from 12 PM to 8 PM)** :clock3:
    - `Hello {User}!`
    - `You are great {User}`
- **Night (from 9 PM to 6 AM)** :zzz:
    - `Have a good night, {User}`
    - `Wish you sweet dreams {User} ...`
    - `It was a great day! {User} it's time to relax!`

## Retrospective
