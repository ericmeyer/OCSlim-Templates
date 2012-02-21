##Installation

### Cloning the templates
<pre>
  git clone git://github.com/ericmeyer/OCSlim-Templates.git ~/Library/Developer/Xcode/Templates/
  Restart Xcode
</pre>

## Using with a project
**Do not use the Project Templates**

1. Create a new project or Open an existing project
2. File -> New -> New Target
3. Under iOS, select "OCSlim-Templates" and choose the iPhoneRunner
4. `cd <PROJECT_ROOT>`
5. `chmod +x ./bin/iPhoneRunner/OneTimeSetup`
6. `./bin/iPhoneRunner/OneTimeSetup`

## Writing Tests

1. ./bin/StartFitnesse
2. see fitnesse.org for how to write tests
