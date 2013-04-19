## Contributing

See: https://github.com/ericmeyer/ObjectiveCSlim

##Installation

### Cloning the templates
<pre>
  git clone git://github.com/ericmeyer/OCSlim-Templates.git ~/Library/Developer/Xcode/Templates/OCSlim-Templates
  cd ~/Library/Developer/Xcode/Templates/OCSlim-Templates
  git submodule update --init
  Restart Xcode
</pre>

## Using with a project
**Do not use the Project Templates**

1. Create a new project or Open an existing project
2. File -> New -> New Target
3. Under iOS, select "OCSlim-Templates" and choose the iPhoneRunner for an iOS app or MacRunner for Mac app.
4. After adding the target, add `-fno-objc-arc` to the Compiler Flags for OCSReturnValue.m under the "Build Phases" for you new target.
5. `cd <PROJECT_ROOT>`
6. `./bin/OneTimeSetup`

## Writing Tests

1. ./bin/StartFitnesse
2. see fitnesse.org for how to write tests
