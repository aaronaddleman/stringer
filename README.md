# stringer

following the tutorial located at https://www.thorsten-hans.com/lets-build-a-cli-in-go-with-cobra/

## getting started

``` shell
# create the project folder
mkdir stringer && cd stringer

# initialize the project
go mod init github.com/aaronaddleman/stringer

# create the repository structure
mkdir -p cmd/stringer
mkdir -p pkg/stringer

touch cmd/stringer/root.go
touch pkg/stringer/stringer.go
touch main.go

# add Cobra as a dependency
go get -u github.com/spf13/cobra@latest
```
