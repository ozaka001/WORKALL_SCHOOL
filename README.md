
## ***ผู้จัดทำ***

ดีต้า ต้าศุภกรสงเคราะห์ 010 ป.ตรี 1 สาขา เทคโนโลยีสารสนเทศฯ

# *Fronend Flutter*

> [https://github.com/ozaka001/WORKALL2_SCHOOL]

# *guideline*

> start project 
> go mod init name_project

# *go gin for import use go support API Go*
[enter link description here](https://github.com/gin-gonic/gin)

    use this go get -u github.com/gin-gonic/gin

# *create file for test code with this*

    package main
    
    import ( "net/http"
    
    "github.com/gin-gonic/gin" )
    
    func main() { r := gin.Default() r.GET("/ping", func(c *gin.Context) { c.JSON(http.StatusOK, gin.H{ "message": "pong", }) }) r.Run() // listen and serve on 0.0.0.0:8080 (for windows "localhost:8080") }

# *run go*

    go run .

    test ไปที่ localhost:8080/ping

    go get . ติดตั้ง package ต่างๆ

# *การปิด package กรณียังไม่ใช้งาน*
[enter link description here](_ "golang.org/x/crypto/bcrypt")

  
