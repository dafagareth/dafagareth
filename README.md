# Hey, I'm Dafa Gareth

4th semester SI student at Universitas Putra Indonesia YPTK Padang. I build small,
sharp tools in Go and spend way too much time figuring out how things work under
the hood. Daily driving Arch Linux (yes, btw).

Open to internships and freelance work, so feel free to reach out.

```go
package main

type Dafa struct {
	Studying string
	Loves    []string
	Learning []string
	OpenTo   string
}

func main() {
	_ = Dafa{
		Studying: "SI @ UPI YPTK, semester 4",
		Loves:    []string{"Go", "the terminal", "clean simple code"},
		Learning: []string{"distributed systems", "Kubernetes", "Go concurrency"},
		OpenTo:   "internship / freelance",
	}
}
```

## Stuff I'm building

- **[svault](https://github.com/dafagareth/VaultCLI)** is a local encrypted secret
  vault CLI in Go. AES-256-GCM, Argon2id, single binary, zero dependencies. Made it
  because I was tired of secrets sitting in plain `.env` files. Comes with tests, CI,
  and packaging for a few platforms.
- **My portfolio + blog**, server-rendered in Go with Chi, templ, HTMX, and Tailwind.
  No JS framework, just fast SSR.

## How I like to work

- Simple beats clever, every time
- Write code the next person can actually read
- Docs are part of the product, not an afterthought

## Say hi

- Email: dafagareth@gmail.com
<!-- - Blog: [dafagareth.dev](https://dafagareth.dev)-->

<!--
Optional GitHub stats. Uncomment if you want them on your profile.

![Dafa's GitHub stats](https://github-readme-stats.vercel.app/api?username=dafagareth&show_icons=true&hide_border=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=dafagareth&layout=compact&hide_border=true)
-->
