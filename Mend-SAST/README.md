# Mend-demo

example:
mend sast --app "\<Mend SAST Application Name>" --dir \<Local File path>

test.abap container SQL Injection

## mend option
```
$ mend sast --help
Usage:
  mend sast [flags]

Flags:
  -h, --help                                Show help for command
  -c, --config path                         Specifies SAST JSON configuration file path
  -d, --dir directory                       Specifies target directory for SAST analysis
  -a, --app name                            Specifies scan parent application name and inherits its parameters. Use in Mend SAST
  -s, --scope string                        Specifies Mend scope: ORG//APP//PROJECT (partial hierarchy can be set by specifying PROJECT or APP//PROJECT). Use in Mend App
  -t, --template name                       Specifies scan configuration template name
  -n, --name name                           Specifies scan name. Auto-generated if omitted
  -i, --inc                                 Indicates if the scan should be an incremental scan
      --upload-baseline                     Indicates if the scan data should be uploaded as a new baseline for incremental scans
      --baseline-storage path               Custom path for storing incremental data locally. Defaults to cache location
  -r, --report                              Indicates if a report should be created
      --formats formats                     SAST report formats (html, pdf, xml, json, csv or sarif)
      --filename filename                   SAST report filename (extensions will be automatically appended)
  -e, --engines IDs                         Specifies which SAST engines should be used by their IDs (omit for auto-recognition)
      --retries number                      Specifies number of retries in case of scan failures
      --num-cpu number                      Specifies the number of processor units for multicore processing (on Linux CFS quota is applied) (default 2)
      --snippet-size size                   Specifies the size of source code snippets (lines of code) submitted to Mend (default 10)
      --structure path                      Runs the structure analysis of the target directory and saves a report to a provided path
      --no-logs                             Disables the submission of SAST logs to Mend
      --no-color                            Disables colored standard output
      --no-progress                         Disables progress bars in standard output
      --no-default-exclusions               Disables default path exclusions
  -j, --java-engine-generation generation   Specifies which generation of Java detection engine is used to perform the scan. Possible arguments are 1 or 2.
      --no-baseline                         Disables the creation of a baseline dump
```

## Ref:
- [Scan Your Proprietary App Source Code (SAST) with Mend CLI](https://docs.mend.io/bundle/cli/page/scan_your_proprietary_app_source_code__sast__with_mend_cli.html)

