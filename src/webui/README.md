# WebUI

## View summary page

Click the tab "Overview".

* See the experiment parameters.
* See good performance trial.
* See search_space json.

## View job accuracy

Click the tab "Optimization Progress" to see the point graph of all trials. Hover every point to see its specific accuracy.

## View hyper parameter

Click the tab "Hyper Parameter" to see the parallel graph.

* You can select the percentage to see top trials.
* Choose two axis to swap its positions

## View trial status 

Click the tab "Trial Status" to see the status of the all trials. Specifically:

* Trial duration: trial's duration in the bar graph.
* Trial detail: trial's id, trial's duration, start time, end time, status, accuracy and search space file.
* Kill: you can kill a job that status is running.
* Tensor: you can see a job in the tensorflow graph, it will link to the Tensorboard page.

## Control 

Click the tab "Control" to add a new trial or update the search_space file and some experiment parameters.

## Feedback

[Known Issues](https://github.com/Microsoft/nni/issues).