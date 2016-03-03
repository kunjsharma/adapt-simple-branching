# adapt-simple-branching
An Adapt framework extension to add simple branching functionality. Based on the results of the question the simple-branching block can display/hide it's components.

## Installation

Download the ZIP and extract into the src > extensions directory.

## Usage

Add the `_branching` entry to the block that will have alternate content

```
        "_branching": {
            "questionId": "c-05",
            "incorrect": "c-10",
            "correct": "c-15",
            "forceCompletion": false
        }
```

* `questionId` the question component ID which this branching block will listen for results
* `incorrect` the component ID within the branching block that will be displayed when user will answer incorrectly
* `correct` the component ID within the branching block that will be displayed when user will answer correctly
* `forceCompletion` defaults to true, boolean flag indicating if the completion status
