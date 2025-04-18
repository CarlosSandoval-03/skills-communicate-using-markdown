# This is a title \<H1\>

![Image of blacktocats](https://octodex.github.com/images/blacktocats.png)

```c
void secure_recv_long(int socket_fd, long *value)
{
	char buffer[BUFFER_SIZE];
	memset(buffer, 0, BUFFER_SIZE);
	secure_recv_string(socket_fd, buffer, BUFFER_SIZE);
	*value = atol(buffer);
}
```

- [X] A
- [ ] B
- [X] C
