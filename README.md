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
            Node.js::class,
            AWS::class,
            Yii2::class,
            Laravel::class,
            MySQL::class,
            MongoDB::class
            Docker::class,
            JavaScript::class,
            Linux::class,
            OpenAPI::class,
            Software Architecture::class
        ];
    }
    
    public function getGeneralWorkExperience(): string
    {
        return '>9 years';
    }

    public function getFutureGoal(): string
    {
        return 'Deepen my knowledge in building high-load applications.';
    }
}
```
