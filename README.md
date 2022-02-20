# EasyView README

EasyView is an extension atop Vscode.
EasyView can show multiple interactive views for users to go through the profiling data collecte by various tools. Moreover, it supports an easy way to corelate profiling results with program source codes.
Currently, EasyView supports two formats of profiling data: [pprof format](https://github.com/google/pprof/blob/master/proto/profile.proto) and [drcctprof format](https://github.com/Xuhpclab/DrCCTProf). Thus, EasyView can directly open profiling files produced by pprof and DrCCTProf.


## Usage


### Open EasyView

There are three typical ways to open a file in pprof/DrCCTProf formats.

> **Tips:**
*For go pprof output files, you need to unzip them first.*

#### 1. Open EasyView from Vscode Explorer View

(1) Right-click the profile file.

(2) Click "show EasyView".

#### 2. Open EasyView from Vscode Editor View

(1) Click the profile file to open it with editor view.

(2) Click the "show EasyView" button in the top right of the editor view.

#### 3. Make EasyView as the default view by changing the file extension suffix

(1) Add an extension suffix (***.drcctprof***) to the unzipped profile file.

(2) Click the file to open the view of EasyView.

### Use case

#### A demo to explore EasyView
