# sr-echo-pagerduty
SimpleReach PagerDuty app for Amazon Echo

## Usage
Currently in dev
* Will require pagerduty token. Token will be stored in amazon's dynamoDB, hidden through gem devise

## Current Endpoints
### incidents
* Alexa reads back all triggered incidents sorted by desc date
* Alexa reads back last triggered alert
* Alexa can update the incident with your given action
### oncalls
* Alexa responds with current team members on call sorted by priority
### in dev
* Schedules?

## Tests
* Run rspec spec

## Dev
* DynamoDB
** https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/DynamoDBLocal.html
** Download the US-West version and follow the instructions
** table name is users

## TODO
- [x] write moat tests
- [x] fix rubocop
- [x] sandi metz-ify
- [x] index of triggered alerts
- [x] last alert update
- [ ] on call schedules (when am i oncall)
- [ ] elastic beanstalk
- [ ] investigate login/email/token UI from alexa app (account linking?)
- [ ] add coveralls on travis
