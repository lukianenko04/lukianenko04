```php
<?php

namespace EvhenLukianenko;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Praxis',
                'position' => 'Software Developer',
                'period' => 'January 2018 – …'         
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
            MongoDB::class,
            Linux::class,
            Docker::class,
            Javascript::class,
            Vuejs::class,
            HTML::class,
            CSS::class,  
        ];
    }
    
    public function getGeneralWorkExperience(): string
    {
        return '>8 years.';
    }

    public function getFutureGoal(): string
    {
        return 'To learn ReactJS and deepen my knowledge in building high-load applications.';
    }
}
```