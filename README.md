# Explanation
This is my practice repository for gin in golang.

# Structure
The structure of this repository is as follows.
```
.
├── go.mod
├── go.sum
├── handler
│   └── handler.go
└── main.go
```

# Usage
You can use this repository as follows.

1. Clone repository
 Clone this repository as follows, then you can get this repository under currect directory as `Golang_gin_totorial`.

```
 git clone git@github.com:mae-commits/Golang_gin_tutorial.git
```

2. Install packages
 To install packages needed to execute this repository, run `go mod init "gin_practice"` firstly. Then, `go mod tidy` to check packages for run.
3. Run codes
 `go run .` to run the app.
4. Access the app
 You can access the app on `localhost:8080/albums`, check this on your browser.

# Functions
 Functions of this app is very simple; only GET, POST, GET from the id.