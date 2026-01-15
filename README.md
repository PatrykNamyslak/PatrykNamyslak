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
    // Clickable links can be found at the end of the README
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
<a href="https://patl.ink/resume-builder" target="_blank" rel="noopener noreferrer">Resume Builder</a><br>

<a href="https://patl.ink/form-builder" target="_blank" rel="noopener noreferrer">Form Builder</a><br>

<a href="https://patl.ink/php-auth" target="_blank" rel="noopener noreferrer">Authentication Facade</a><br>

<a href="https://patl.ink/frontend-foundry" target="_blank" rel="noopener noreferrer">Frontend Foundry</a><br>

<a href="https://patl.ink/patbase" target="_blank" rel="noopener noreferrer">Database Communication Interface</a><br>

<a href="https://patl.ink/flag-api-demo" target="_blank" rel="noopener noreferrer">Flag API: Demo</a><br>

<a href="https://patl.ink/flag-api" target="_blank" rel="noopener noreferrer">Flag API: Source Code</a><br>

<a href="https://patl.ink" target="_blank" rel="noopener noreferrer">Url Shortener: Demo</a><br>

<a href="https://patl.ink/repo" target="_blank" rel="noopener noreferrer">Url Shortener: Source Code</a><br>