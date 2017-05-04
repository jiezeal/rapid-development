#[rapid] 快速开发

```
$.ajaxSetup({
	headers: { 'X-CSRF-TOKEN' : '{{ csrf_token() }}' }
});
```

```
layer.load(1, {shade: [0.1,'#000'],});
layer.closeAll('loading');
```

```
php artisan migrate:rollback
```

查看laravel版本
```
php artisan --version
```

将PHP时间戳转换成日期格式
```
timeConvert(time){
    var date = new Date(parseInt(time)*1000);
    var year = date.getFullYear();
    var month = (date.getMonth()+1) < 10 ? '0'+(date.getMonth()+1) : (date.getMonth()+1);
    var today = date.getDate() < 10 ? '0'+date.getDate() : date.getDate();
    var hour = date.getHours() < 10 ? '0'+date.getHours() : date.getHours();
    var minutes = date.getMinutes() < 10 ? '0'+date.getMinutes() : date.getMinutes();
    var seconds = date.getSeconds() < 10 ? '0'+date.getSeconds() : date.getSeconds();
    var time = year+'-'+month+'-'+today+' '+hour+':'+minutes+':'+seconds;
    return time;
}
```