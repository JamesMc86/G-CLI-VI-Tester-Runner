# G-CLI-VI-Tester-Runner
G CLI Tool to Run VI Tester from the command line

# Requirements

* LabVIEW 2014 or higher.

## Parameters

Name: viTester

### Optional

* -xml: Path for a junit xml output.

### Required

* LV Project Path

### Returns

If xml is provided this step will return nothing.

If it isn't provided then it will return exit code 42 if the tests fail and output the text details to the console.

### Example Call

g-cli --lv-ver 2015 viTester -- -xml test_results.xml "LabVIEW Source/MyProject.lvproj"
