## Goal

This project provide a template to develop a custom view in [Power Platform](https://powerplatform.microsoft.com/en-us/) [Model Driven Application](https://docs.microsoft.com/en-us/powerapps/maker/model-driven-apps/model-driven-app-overview)


This project is a combination of projects below

* [DetailListGrid](https://github.com/rwilson504/PCFControls/tree/master/DetailListGrid) 
  > Reused the code
* [pcf-template-dataset](https://github.com/rajyraman/pcf-template-dataset)  
  > Reused the actions

## The Control

**DetailsList Grid Control** allows you to simulate the out of the box grid and subgrid controls using the [FluentUI DetailsList control](https://developer.microsoft.com/en-us/fluentui#/controls/web/detailslist). It is built to provide a ready-to-use scaffold  when you need a customizable grid experience.  This component re-creates a mojority of the capabilities available out of the box

### Features

1. Using the DataSet within a React functional component.
1. Displaying and sorting data within the [FluentUI DetailsList control](https://developer.microsoft.com/en-us/fluentui#/controls/web/detailslist).
1. Rendering custom formats for data with the DetailsList component such as **links** for **Entity References**, **email addresses** and **phone numbers**.
1. Displaying field data for related entities.
1. React Hooks - the component uses both useState and useEffect.
1. Support DataSet Paging.
1. Retaining the use of the standard ribbon buttons by using the `setSelectedRecordIds` function on the DataSet.
1. Support single selection

Note:
> Currently it doesn't support Canvas-App but only Model-Driven-App

## References

* [Use custom controls for model-driven app data visualizations](https://docs.microsoft.com/en-us/powerapps/maker/model-driven-apps/use-custom-controls-data-visualizations)