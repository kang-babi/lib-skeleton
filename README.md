# Library Project Skeleton

This is a custom project skeleton for creating a PHP library, preconfigured with essential tools for code quality and testing.

## Features

- **Code Formatting:** [Laravel Pint](https://github.com/laravel/pint)  
- **Code Refactoring:** [Rector](https://github.com/rectorphp/rector)  
- **Testing Framework:** [PestPHP](https://pestphp.com/)  
- **Static Analysis:** [PHPStan](https://phpstan.org/)  

## Getting Started

### 1. Create a New Project

To start a new project using this skeleton, run:

```sh
composer create-project kang-babi/lib-skeleton my-library
cd my-library
```

### 2. Install dependencies

```sh
composer install
```

### 3. Run Tests

The test suite is already set up. You can run tests with:

```sh
composer test
```

This will execute the PestPHP test suite.

### 4. Code Quality Checks

- **Format code** with Pint:

  ```sh
  composer lint
  ```

- **Apply automated refactoring** with Rector:

  ```sh
  composer refactor
  ```
  
- **Apply lint and refactor**:

  ```sh
  composer apply
  ```

- **Run static analysis** with PHPStan:

  ```sh
  composer test:types
  ```
