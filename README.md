# Task Management System

## Download project or clone using given command
```
git clone https://github.com/Azeem641/task-management-system.git
```

then run following commands
```
composer install
```

```
php artisan optimize
```

```
php artisan serve
```

# Data Base

## Tables

### Projects
cloumns
```
id (primary key, auto incremented, integer)
name(varchar)
created_at(timestamps)
```

### Tasks
Columns
```
id (primary key, auto incremented, integer)
priority(varchar)
project_id(integer)
name(varchar)
created_at(timestamps)
```
