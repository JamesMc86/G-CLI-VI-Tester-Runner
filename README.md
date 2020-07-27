# G-CLI-VI-Tester-Runner
G CLI Tool to Run VI Tester from the command line

# Requirements

* LabVIEW 2015 or higher.

## Parameters

Name: viTester

### Optional

* -xml: Path for a junit xml output.

### Required

* LV Project Path

### Returns

Returns exit code 1 for a test failure.

### Example Call

g-cli --lv-ver 2015 viTester -- -xml test_results.xml "LabVIEW Source/MyProject.lvproj"
