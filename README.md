# ML-Problem

Error

Can't load type Microsoft.ML.IPredictorProducing`1[System.Single], because it has both create and
constructor methods with the same visibility. Please indicate which one should be used by changing 
either the signature or the visibility of one of them.

````
var mlContext = new MLContext();
var modelPath = @"MLModel.zip";
var mlModel = mlContext.Model.Load(modelPath, out var modelInputSchema);
````
