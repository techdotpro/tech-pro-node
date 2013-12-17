tech-pro-node
=============
An NPM package to manage your tech pro blog and profile.

### Search
```bash
techpro search -t "blogs, tutorials" "JavaScript" --my-network
```

```bash
techpro search -t "profiles" "Leland Richardson"
```

### Blog

```bash
techpro blog list
```

```bash
techpro blog create -n "My new awesome post" -f "my-post.md"
```

```bash
techpro blog 123 update -f "my-post.md"
```

### Profile

```bash
techpro profile update -name "Jonathan Creamer" -about "Some interesting ###facts about me"
```
