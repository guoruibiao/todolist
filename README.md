# introduction of this project.

Just for recording my ideas and thoughts happened suddenly.

Tiny and simple, maybe i will optimize it at some time, who knows.

# architect

- frontend: nginx
- webserver: uwsgi
- web framework: flask, flask_restful
- language:
  - backend: python
  - frontend: javascript, html, css
- database: MySQL

---

# deploy

- `git colne` this repo to your ECS.
- `mysql>source xxx.fortodilist.sql` to serialize your MySQL DataBase, tables.
- `cp todolist.nginx.conf /etc/nginx/conf.d` and modify your own properties which suitable your Nginx server, expecially the static file path.
- make sure every software works fine, then begin your trip :)
