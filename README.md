# issue-1924-evidence

Evidence screenshot for [zhu1090093659/dsh-web](https://github.com/zhu1090093659/dsh-web) issue about
`dsh-remote-web-ui`'s loopback proxy rebuilding the forwarded request headers from a whitelist.

Compares the headers an upstream route actually receives **before** and **after** the minimal patch.
Rendered from real probe output (`pipeLoopbackHttp` extracted from the installed bundle).

Fully redacted: no host, IP, username, token, file path or session content.
