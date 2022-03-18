# beam-go

### Commands for running the Go beam

#### Get version of Go using following command
- go version
#### Get the go sdk using below command
- go get -u github.com/apache/beam/sdks/v2/go/pkg/beam
- go get github.com/apache/beam/sdks/v2/go/pkg/beam/runners/dataflow/dataflowlib@v2.37.0
#### Install wordcount example using following command
- go install github.com/apache/beam/sdks/v2/go/examples/wordcount
#### Generate the wordcount output using following command
- wordcount --input sample.txt --output kurra_counts