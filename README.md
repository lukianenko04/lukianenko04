```php
<?php

namespace EvhenLukianenko;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'NDA',
                'position' => 'Senior Software Engineer | Team Lead',
                'period' => 'May 2022 – …'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            PHP::class,
            AWS::class,
            YII2::class,
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
        return '>8 years';
    }

    public function getFutureGoal(): string
    {
        return 'Deepen my knowledge in building high-load applications.';
    }
}
```