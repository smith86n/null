# null
jobs:   include:     - stage: test       script: ./test 1   yo yo   - # stage name not required, will continue to use `test`       script: ./test 2     - stage: deploy       script: ./deploynull
