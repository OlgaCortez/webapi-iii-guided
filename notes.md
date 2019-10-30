# Middleware Notes

** EVERYTHING IS MIDDLEWARE **

Well, almost everything :-)

## Jargon
Separation of Concerns.
-We do NOT write code for the computer, code is a communication device, a way to reveal our intentions to the next developer.
-Optimize code for readability.

## Types (based on how we got it or who built it)

-built in: included with express. (ex: `express.json()`)
-third party: must be installed from `npm` or `yarn` (third party example).
-custom: we code these!!

## Types (based on how it's being used)

-global: runs on every request

-Order matters: It goes from top to bottom and left to right.
