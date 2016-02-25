Brads Robo Runner
================================================================================
This is a custom [Robo](http://robo.li/) Runner, that does not require an actual
_"RoboFile.php"_ just a class of your choosing.

See: https://github.com/Codegyre/Robo/pull/242

If the above PR is merged, then this class will become redundant.

Installation:
--------------------------------------------------------------------------------

    composer require brad-jones/robo-runner

Example Usage:
--------------------------------------------------------------------------------
```php
// This class could be autoloaded for example.
class MyRoboClass
{
	// tasks...
}

// To run robo
(new Brads\Robo\Runner(MyRoboClass::class))->execute();
```
