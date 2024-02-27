# 選用 Golang 環境的版本
FROM golang:1.14.6-alpine

# 因為 Golang 下載模組需要 Git，我們透過 apk 來安裝
RUN apk add --no-cache git


# 安裝 Golang 連線 PostgreSQL 的模組
RUN go get github.com/lib/pq



