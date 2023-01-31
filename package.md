# aws package
```
package main

import (
	"os"
	"context"
	"log"
	"net/http"

	"github.com/gin-gonic/gin"
	"github.com/aws/aws-sdk-go-v2/aws"
	"github.com/joho/godotenv"
	"github.com/aws/aws-sdk-go-v2/feature/s3/manager"
	"github.com/aws/aws-sdk-go-v2/config"
	"github.com/aws/aws-sdk-go-v2/service/s3" 
)
```