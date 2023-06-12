## <p align="center"><a href="https://github.com/stermso/Paper-Design/blob/paper-design-nodeJS%40eggJS/README.md">中文</a> | <a href="https://github.com/stermso/Paper-Design/blob/paper-design-nodeJS%40eggJS/README.en.md">English</a></p>

### 一.api
1. /find , get , m ; [data query]

2. /bookDetail , get ; id , [id query]

3. /getHistory , get ; [get history]

4. /getCollect , get ; [get collection]

5. /getNews , get ; [get new books]

### 二.manage
1. /collect , post , id ; [collect by id and recovery to corresponding array]

2. /cancel , post , id ; [cancel collect by id and recovery to corresponding array]

3. /doAdd , post ; (form:m,title,abstract,authors,imgUrl,news,collected,) [add books]

4. /delete , post , id ; [delete books by id]

5. /change , post , id(get) ，from(title,authors,abstract,collected,news,imgUrl) ; [change books by id]

6. /search , get , keyword(get) ; [return search result of 'res']  [serach by keywords]

7. /history , get , id(get) ; [add history by id]

8. /login ; [The user name and password are correct, and the cache is set, otherwise it is prompted to make an error]

9. /logout ; [delete cache , logout]

10. /addNews , post , id ; [add new books by id]

11. /cancelNews , post , id ; [delete new books by id]