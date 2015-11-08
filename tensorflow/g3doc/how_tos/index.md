# Overview <a class="md-anchor" id="AUTOGENERATED-overview"></a>


## Variables: Creation, Initializing, Saving, and Restoring <a class="md-anchor" id="AUTOGENERATED-variables--creation--initializing--saving--and-restoring"></a>

TensorFlow Variables are in-memory buffers containing tensors.  Learn how to
use them to hold and update model parameters during training.

[View Tutorial](../how_tos/variables/index.md)


## TensorFlow Mechanics 101 <a class="md-anchor" id="AUTOGENERATED-tensorflow-mechanics-101"></a>

A step-by-step walk through of the details of using TensorFlow infrastructure
to train models at scale, using MNIST handwritten digit recognition as a toy
example.

[View Tutorial](../tutorials/mnist/tf/index.md)


## TensorBoard: Visualizing Learning <a class="md-anchor" id="AUTOGENERATED-tensorboard--visualizing-learning"></a>

TensorBoard is a useful tool for visualizing the training and evaluation of
your model(s).  This tutorial describes how to build and run TensorBoard as well
as how to add Summary ops to automatically output data to the Events files that
TensorBoard uses for display.

[View Tutorial](../how_tos/summaries_and_tensorboard/index.md)


## TensorBoard: Graph Visualization <a class="md-anchor" id="AUTOGENERATED-tensorboard--graph-visualization"></a>

This tutorial describes how to use the graph visualizer in TensorBoard to help
you understand the dataflow graph and debug it.

[View Tutorial](../how_tos/graph_viz/index.md)


## Reading Data <a class="md-anchor" id="AUTOGENERATED-reading-data"></a>

This tutorial describes the three main methods of getting data into your
TensorFlow program: Feeding, Reading and Preloading.

[View Tutorial](../how_tos/reading_data/index.md)


## Threading and Queues <a class="md-anchor" id="AUTOGENERATED-threading-and-queues"></a>

This tutorial describes the various constructs implemented by TensorFlow
to facilitate asynchronous and concurrent training.

[View Tutorial](../how_tos/threading_and_queues/index.md)


## Adding a New Op <a class="md-anchor" id="AUTOGENERATED-adding-a-new-op"></a>

TensorFlow already has a large suite of node operations from which you can
compose in your graph, but here are the details of how to add you own custom Op.

[View Tutorial](../how_tos/adding_an_op/index.md)


## Custom Data Readers <a class="md-anchor" id="AUTOGENERATED-custom-data-readers"></a>

If you have a sizable custom data set, you may want to consider extending
TensorFlow to read your data directly in it's native format.  Here's how.

[View Tutorial](../how_tos/new_data_formats/index.md)


## Using GPUs <a class="md-anchor" id="AUTOGENERATED-using-gpus"></a>

This tutorial describes how to construct and execute models on GPU(s).

[View Tutorial](../how_tos/using_gpu/index.md)


## Sharing Variables <a class="md-anchor" id="AUTOGENERATED-sharing-variables"></a>

When deploying large models on multiple GPUs, or when unrolling complex LSTMs
or RNNs, it is often necessary to access the same Variable objects from
different locations in the model construction code.

The "Variable Scope" mechanism is designed to facilitate that.

[View Tutorial](../how_tos/variable_scope/index.md)

<div class='sections-order' style="display: none;">
<!--
<!-- variables/index.md -->
<!-- ../tutorials/mnist/tf/index.md -->
<!-- summaries_and_tensorboard/index.md -->
<!-- graph_viz/index.md -->
<!-- reading_data/index.md -->
<!-- threading_and_queues/index.md -->
<!-- adding_an_op/index.md -->
<!-- new_data_formats/index.md -->
<!-- using_gpu/index.md -->
<!-- variable_scope/index.md -->
-->
</div>
