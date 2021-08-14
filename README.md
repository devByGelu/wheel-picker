# WheelPicker

WheelPicker component for Collude.

**API**
| Name                            | Description                                                                                                       | Required | default   |
|---------------------------------|-------------------------------------------------------------------------------------------------------------------|----------|-----------|
| @Input() option: Option[ ]      | Options for the picker.                                                                                           | Yes      |           |
| @Input() windowLength: number   | Number of items to show in the wheelpicker. Must be an Odd number to position selected on the midddle.            | No       | 1         |
| @Input() btnMargin: number      | applies:     1. margin-bottom: {btnMargin}px 2. margin-top: {btnMargin}px  for up and down buttons respectively.  | No       | 10        |
| @Input() unit: string           | Adds a unit beside the selected option.                                                                           | No       | undefined |
| handleNewSelectedEvent : Option | Returns the selected option.                                                                                      | Yes      |           |



**DEMO**
![image](https://user-images.githubusercontent.com/41291228/129440022-75532c67-6896-465a-87da-5460e834cb71.png)
