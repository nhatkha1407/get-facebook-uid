Code JS lấy toàn bộ UID từ 1 page / post / group...

Quick start
```javascript
wRun('auto');
hoặc
wRun();
```


Other options

```javascript
wRun(1);            // Scroll trong 1 phút
wRun('auto');       // Nếu là trang members- scroll 10 phút, ngược lại- scroll 1 phút. User Count 1000. 
wRun('infinity');   // Scroll đến khi hết trang hoặc.. bị lỗi.. =)).

wRun('comments');   // Load Comment Links
wRun('replies');    // Load Reply Links
wRun('result');     // Lấy UID

wRun({ timeout: 5, userCount: 200 }); // Scroll trong 5 phút hoặc lấy được khoảng 200 UID thì dừng.
```