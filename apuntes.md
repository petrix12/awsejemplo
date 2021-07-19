# Aprende a instalar Laravel 8 en Amazon Web Services
###### https://www.udemy.com/course/aprende-a-instalar-laravel-8-en-amazon-web-services

## Sección 1: Introducción

### Video 01. Crear un proyecto de Laravel
1. Crear un proyecto de Laravel:
    + $ laravel new awsejemplo
1. Instalar Jetstream al proyecto:
    + $ composer require laravel/jetstream
1. Instalar livewire:
    + $ php artisan jetstream:install livewire
1. Crear base de datos **awsejemplo** con phpMyAdmin.
1. Ejecutar migraciones:
    + $ php artisan migrate
1. Ejecutar:
    + $ npm install
    + $ npm run dev

### Video 2. Subir el proyecto a GitHub
1. Ir a https://github.com (Crea una cuenta si aún no la tienes)
1. Crear un nuevo repositorio y nombrarlo **awsejemplo**.
1. Descargar e instalar **Git** en https://git-scm.com.
1. En local ejecutar:
    + $ git init
    + $ git add .
