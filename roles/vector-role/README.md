# Vector Role

Роль для установки Vector.

## Переменные

| Переменная | Описание | По умолчанию |
|------------|----------|-------------|
| vector_version | Версия Vector | 0.34.0 |
| vector_install_dir | Директория установки | /opt/vector |
| vector_config_dir | Директория конфигов | /etc/vector |

## Пример использования

```yaml
- hosts: vector
  roles:
    - vector-role
```
