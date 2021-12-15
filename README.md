
![Read Me Header Image 3](https://user-images.githubusercontent.com/95258461/145036180-9be092bb-9097-4ad5-b7e2-5b5b0e163613.png)

# Ship Detector Description

In these exercises, you will use the Custom Vision service to train an object detection model that can detect and locate ships in a satellite image, call the model through Python code in a notebook, and then build Power BI visualizations.
Note: These exercises are built with open-source imagery. Other imagery can be used in combination with the example code and fully customized for a complete end to end solution.

## Prerequisite

- Active Azure subscription
- At least contributor access to Azure subscription
- A VSCode environment
- A Power BI account and Power BI Desktop

## Getting Started

To deploy this solution in your subscription, follow the manual instructions in the `Ship Detector Instructions.pdf`.

<img width="322" alt="image" src="https://user-images.githubusercontent.com/95258461/144634210-b11ea583-8da7-4081-99df-61498c810c97.png">

## Clone the repository for this course
If you have already cloned ShipDetector code repository to the environment where you're working on this lab, open it in Visual Studio Code; otherwise, follow these steps to clone it now.
1.	Start Visual Studio Code.
2.	Open the palette (SHIFT+CTRL+P) and run a Git: Clone command to clone the `https://github.com/Microsoft/ShipDetection` repository to a local folder (it doesn't matter which folder).
3.	When the repository has been cloned, open the folder in Visual Studio Code.
4.	Wait while additional files are installed to support the Python code projects in the repo. You may need to manually install packages if necessary.

## .env Setup

The `.env` file will need to be edited to hold your key information. A template is provided.
```
PredictionEndpoint=
PredictionKey=
ProjectID=
ModelName=Ship-Detector
Predicted_Object_Threshold=15
```

### References

- [Azure Custom Vision](https://docs.microsoft.com/azure/cognitive-services/custom-vision-service/)
- [Power BI Documentation](https://docs.microsoft.com/en-us/power-bi/)
- [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/)
- [Azure Space](https://azure.microsoft.com/en-us/solutions/space/#overview)

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
