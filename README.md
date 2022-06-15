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
                'position' => 'PHP Developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Vuejs::class,
            Laravel::class,
            Yii2::class,
            MySQL::class,
            MongoDB::class,
            HTML::class,
            CSS::class,
            Linux::class,
            Aws::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To learn ReactJS and contribute to open source.';
    }
}
```