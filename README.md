```PHP

abstract class PatrykNamyslak{
    public static string $name = "Patryk Namyslak";
    public static string $role = "PHP Web Developer";
    public static array $stack = [
        "Frontend" => [
            "Blade",
            "TailwindCSS",
            "Livewire",
            "Vite",
            "HTML",
            "CSS",
            "HTMX"
            ],
        "Backend" => [
            "PHP",
            "Laravel",
            "Redis"
            ],
        "Server" => [
            "Linux",
            "Apache",
            "MySQL"
            ],
        ];
    public static array $projects = [
        "Resume Builder" => "https://patl.ink/php-auth",
        "Form Builder" => "https://patl.ink/php-form-builder",
        "Frontend Foundry" => "https://patl.ink/frontend-foundry",
        "Flag API" => [
            "https://patl.ink/flag-api",
            "https://patl.ink/flag-api-demo"
            ],
        "Url Shortener" => "https://patl.ink/repo", 
        "Database Communication Interface" => "https://patl.ink/patbase",
        ];

    public static function greeting(){
        echo "Hi there! My name is " . self::$name . " and I am a " . self::$role;
    }
}

PatrykNamyslak::greeting();
```

```
worker@patryknamyslak.pl~$ php Patryk.class.php
> Hi there! My name is Patryk Namyslak and I am a Full-stack Web Developer
```