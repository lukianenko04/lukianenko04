```php
<?php

namespace YevhenLukianenko;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'NDA',
                'position' => 'Senior Software Engineer',
                'period' => 'Jan 2018 – …'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            PHP::class,
            AWS Services::class,
            Node.js::class,
            TypeScript::class,
            JavaScript::class,
            Yii2::class,
            MySQL::class,
            MongoDB::class
            Docker::class,
            Jenkins::class,
            Linux::class,
            Software Architecture::class,
            Web Security::class
        ];
    }
    
    public function getGeneralWorkExperience(): string
    {
        return '>10 years';
    }

    public function getFutureGoal(): string
    {
        return 'Deepen my knowledge in building high-load applications.';
    }
}
```
