# Interledger Technical Test for the [Senior Technical Writer Role](https://interledger-foundation.breezy.hr/p/1aa5d4fb353c-senior-technical-writer)

## Logistics
This challenge is intended to be done at home. You should write the code in the programming language of your choice and you may use any resources you like. You are encouraged to use any libraries that you find helpful.

We will schedule a review session afterwards with our CTO, via video call. We will ask you to discuss your deliverables, explain your SSG choices, and pair-program a feature live.

_Please do not share this challenge or your solution to it._

## Challenge

Create the following resources to document the "icanhazdadjoke" REST API:

- single page overview that outlines the concepts and functionality of the API
- OpenAPI specification for the search endpoint
- 500-1000 word step-by-step tutorial for using the API endpoint using the programming language of your choice.

### Constraints

- write the documentation in Markdown
- use a SSG to display the documentation
- the API has no authentication, supports multiple response formats and requires a user agent 


### Example Usage of the API

```sh
$ curl -H "Accept: application/json" -H "User-Agent: ILF Test (https://github.com/username/repo" https://icanhazdadjoke.com/search
```

