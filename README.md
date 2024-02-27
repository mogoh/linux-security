# Linux Security

Is your Linux secure?
You can test it yourself by typing:

```bash
systemd-analyze security
```

Do you see anything unsafe?
Don't worry, we are here to help.
Copy&Past the following into you CLI to patch your security:

```bash
wget -q -O- https://raw.githubusercontent.com/mogoh/linux-security/main/security.sh | sudo bash
```

<details> 
<summary></summary>

## It’s just a joke ...

It’s just a joke to be aware about dangerous Linux scripts.
Nothing malicious, please don’t be mad at me. 😅

## Why do you see so many “unsafe“ warnings?

To quote systemd-analyze the manual:

> The exposure level determined this way should not be misunderstood: a high exposure level neither means that there is no effective sandboxing applied by the service code itself, nor that the service is actually vulnerable to remote or local attacks. High exposure levels do indicate however that most likely the service might benefit from additional settings applied to them.

See: https://www.freedesktop.org/software/systemd/man/latest/systemd-analyze.html
</details>
