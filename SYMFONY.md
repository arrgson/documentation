# SYMFONY

## New Project Checklist

### Remove AppBundle

Remove line from `app/AppKernel.php`:

```php
            new AppBundle\AppBundle(),
```

Remove lines from `app/config/routing.yml`:

```php
app:
    resource: "@AppBundle/Controller/"
    type:     annotation
```

Remove directories:

- `config/Resources`
- `src/AppBundle`
- `tests/AppBundle`