# go-gin-quickStart
show how to start to build a project with gin web frame

step1: create a new project on local environment

![image](https://user-images.githubusercontent.com/83266822/156319840-2453e232-205c-4ed1-93ba-0784747b1eb4.png)

step2: create a new github repositores on website to manage our project branch with github

![image](https://user-images.githubusercontent.com/83266822/156320757-13099bf2-5f77-4456-b455-403c628f56fb.png)

![image](https://user-images.githubusercontent.com/83266822/156320814-bf5ba4de-c3a7-436b-a4dc-e21299ce15e7.png)

step3: download git(if u not installed yet) and enter git init [ur project name] just like here

![image](https://user-images.githubusercontent.com/83266822/156321185-82d1b709-def9-4fd7-9bde-7a8cf25e5ae7.png)

step4: build relationships between local branch and orgin one on github

![image](https://user-images.githubusercontent.com/83266822/156321532-4db4d110-dd11-436a-9504-8bca2adac012.png)

step5: push ur code to master orgin

![image](https://user-images.githubusercontent.com/83266822/156321837-cc25626b-aa6e-49a7-bf87-71648c0bcd5c.png)

![image](https://user-images.githubusercontent.com/83266822/156321868-dc75930b-b343-49bf-9b08-232724b59416.png)


#go gin quick start#

a simple main.go

func main() {
	r := gin.Default()
	r.GET("/ping", func(c *gin.Context) {
		c.JSON(200, gin.H{
			"message": "pong",
		})
	})
	r.Run() // listen and serve on 0.0.0.0:8080 (for windows "localhost:8080")
}

run and get with postman

![image](https://user-images.githubusercontent.com/83266822/156326962-d969fd5c-2328-4155-80d4-25aaa34f1c85.png)

![image](https://user-images.githubusercontent.com/83266822/156327009-de839c7d-0c0b-4e04-87c1-fdd57a89402a.png)

sucess!
