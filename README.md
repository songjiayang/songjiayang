```golang
func main() {
	profile := `
Hi there 👋
Thanks for visiting my GitHub profile, it's great to meet you here! 😊

Here are some quick things about me:
`
	fmt.Println(profile)
	
	me := map[string]string{
		"name":    "songjiayang",
		"job":     "Software Engineer",
		"company": "JDCloud",
	}
	for k, v := range me {
		fmt.Printf("- %s: %s \n", k, v)
	}

}
```
