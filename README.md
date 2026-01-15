```PHP
// TODO: MAKE THE LINKS CLICKABLE
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
        "Resume Builder" => "https://patl.ink/resume-builder", # TBA
        "Form Builder" => "https://patl.ink/form-builder",
        "Authentication Facade" => "https://patl.ink/php-auth",
        "Frontend Foundry" => "https://patl.ink/frontend-foundry",
        "Database Communication Interface" => "https://patl.ink/patbase",
        "Flag API" => [
            "Source Code" => "https://patl.ink/flag-api",
            "Demo" => "https://patl.ink/flag-api-demo"
            ],
        "Url Shortener" => [
            "Source Code" => "https://patl.ink/repo",
            "Demo" => "https://patl.ink",
            ], 
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

# Projects (With Clickable links)
https://patl.ink/resume-builder <br>
https://patl.ink/form-builder <br>
https://patl.ink/php-auth <br>
https://patl.ink/frontend-foundry <br>
https://patl.ink/patbase <br>
https://patl.ink/flag-api <br>
https://patl.ink/flag-api-demo <br>
https://patl.ink/repo <br>
https://patl.ink <br>