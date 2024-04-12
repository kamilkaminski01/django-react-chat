<h1 align="center">Django & React Chat</h1>

Django & React Chat is a web app, where users can provide their username,
join the chat and converse with each other. When users join or leave the chat
others get notified about it.

![demo](https://raw.githubusercontent.com/kamilkaminski01/django-react-chat/main/frontend/src/assets/images/demo.png)

## Resources

### Backend
- [Django](https://www.djangoproject.com/)
- [Django Channels](https://channels.readthedocs.io/en/latest/)

### Frontend
- [Vite](https://vitejs.dev/)
- [React](https://react.dev/)
- [SASS](https://sass-lang.com/)

### DevOps
- [Docker](https://www.docker.com/)
- [Redis](https://redis.io/)

## Running from sources

### Docker Compose setup

```bash
git clone https://github.com/kamilkaminski01/django-react-chat.git
cd django-react-chat/
make build
make run
```

If `make` is not supported, the associated Docker Compose commands can be used in order to build
and run the project:
```bash
git clone https://github.com/kamilkaminski01/django-react-chat.git
cd django-react-chat/
docker compose build
docker compose up
```
