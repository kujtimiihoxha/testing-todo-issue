# Test case for todo-issue
This project is created to demonstrate the use of [todo-issue](https://github.com/kujtimiihoxha/todo-issue) in a maven project.
## Try it
You can clone this repository and test todo-issue.

- Clone repository
- Create todo.json in the working directory (where pom.xml is)
```json
{
  "git-server":"Github",
  "gitlab-url":"https://gitlab.com/",
  "repository-username":"kujtimiihoxha",
  "issuer-username":"{your-user}",
  "token":"{your-token}",
  "repository":"testing-todo-issue"
}
```
- Add an issue like described [here](https://github.com/kujtimiihoxha/todo-issue#syntax)
- Run ```mvn clean install```

Go to [issues page](https://github.com/kujtimiihoxha/testing-todo-issue/issues) and see your issues appear.

Close any issue you created and run ```mvn clean install``` again and you will se the todo-s will disappear from the source file.