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
