# reason-native-cli-template


[![CircleCI](https://circleci.com/gh/yourgithubhandle/reason-native-cli-template/tree/master.svg?style=svg)](https://circleci.com/gh/yourgithubhandle/reason-native-cli-template/tree/master)


**Contains the following libraries and executables:**

```
reason-native-cli-template@0.0.0
│
├─test/
│   name:    TestReasonNativeCliTemplate.exe
│   main:    TestReasonNativeCliTemplate
│   require: reason-native-cli-template.lib
│
├─library/
│   library name: reason-native-cli-template.lib
│   namespace:    ReasonNativeCliTemplate
│   require:
│
└─executable/
    name:    ReasonNativeCliTemplateApp.exe
    main:    ReasonNativeCliTemplateApp
    require: reason-native-cli-template.lib
```

## Developing:

```
npm install -g esy
git clone <this-repo>
esy install
esy build
```

## Running Binary:

After building the project, you can run the main binary that is produced.

```
esy x ReasonNativeCliTemplateApp.exe 
```

## Running Tests:

```
# Runs the "test" command in `package.json`.
esy test
```
