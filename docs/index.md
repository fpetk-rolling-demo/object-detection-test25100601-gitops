# **AI Software Template GitOps**

This repository contains the necessary content required for managing GitOps. It was created as part of an AI Software Template execution. The associated source component is available for reference in the **Overview** tab as described in the following image.

![Overview Tab](./images/overview-dependency.png)

# **Deployed Resources**

A deployment with the following characteristics was made based on input from the AI Software Template.

## **Model & Model Server**

A [detr-resnet-101]( https://github.com/containers/ai-lab-recipes/tree/main/model_servers/object_detection_python) model server was deployed to serve the []() model.

!!! info

    This model server is available on port 8000!

# **Application**

The AI Software Template that was executed comes with a sample application. This application will be built from https://github.com/fpetk-rolling-demo/object-detection-test25100601, stored in [quay.io/tpetkos/object-detection-test25100601](https://quay.io/tpetkos/object-detection-test25100601) and deployed through ArgoCD. 

This sample application is accessible through port 8501.