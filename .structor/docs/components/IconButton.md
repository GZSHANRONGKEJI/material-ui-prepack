```
//Method 1: muidocs-icon-github is defined in a style sheet.
<IconButton iconClassName="muidocs-icon-custom-github" tooltip="GitHub"/>
//Method 2: ActionGrade is a component created using mui.SvgIcon.
<IconButton tooltip="Star" touch={true}>
  <ActionGrade/>
</IconButton>
//Method 3: Manually creating a mui.FontIcon component within
IconButton
<IconButton tooltip="Sort" disabled={true}>
  <FontIcon className="muidocs-icon-custom-sort"/>
</IconButton>
//Method 4: Using Google material-icons
 <IconButton iconClassName="material-icons" tooltipPosition="bottom-center"
  tooltip="Sky">settings_system_daydream</IconButton>
```

-----
This component generates a button element and all props. Also, focus styles will happen on tab but not on click. There are three ways to add an icon:

For stylesheets: Set the prop "iconClassName" to the classname for you icon.
For svg icons: Insert the svg component as a child of icon buttons. This is the method we are using. View our source to see how ActionGrade was created using mui.SvgIcon.
Alternative: You can also insert a FontIcon component as a child of IconButton. This is similiar to how the iconClassName prop from method 1 is handled.
Google Material Icons: Now also supported for iconButtons by passing "material-icons" in iconClassName prop.

-----

<div data-reactid=".0.$=12:0.0.0.1:3"><div style="font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:0px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;border-top:none;margin-top:0px;" data-reactid=".0.$=12:0.0.0.1:3.$0"><h3 style="font-size:20px;line-height:28px;padding-top:19px;margin-bottom:13px;letter-spacing:0px;font-weight:500;color:rgba(0, 0, 0, 0.87);box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.0">Props</h3><table style="border-collapse:collapse;border-spacing:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1"><tbody data-reactid=".0.$=12:0.0.0.1:3.$0.1.0"><tr data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$0"><td style="padding: 32px 24px 32px 0px; vertical-align: top; position: inherit; font-weight: 500; box-sizing: border-box; min-width: 128px;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$0.0">iconClassName</td><td style="padding: 32px 0px; vertical-align: top; width: 100%; border-bottom-style: solid; border-bottom-width: 1px; border-bottom-color: rgb(224, 224, 224); box-sizing: border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$0.1"><p style="margin:0px;font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:0px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$0.1.0"><span style="color:rgba(0, 0, 0, 0.54);padding-right:24px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$0.1.0.0">string</span><span data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$0.1.0.1">optional</span></p><p style="margin:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$0.1.1">If you are using a stylesheet for your icons, enter the class name for the icon to be used here.</p></td></tr><tr data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$1"><td style="padding: 32px 24px 32px 0px; vertical-align: top; position: inherit; font-weight: 500; box-sizing: border-box; min-width: 128px;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$1.0">iconStyle</td><td style="padding: 32px 0px; vertical-align: top; width: 100%; border-bottom-style: solid; border-bottom-width: 1px; border-bottom-color: rgb(224, 224, 224); box-sizing: border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$1.1"><p style="margin:0px;font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:0px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$1.1.0"><span style="color:rgba(0, 0, 0, 0.54);padding-right:24px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$1.1.0.0">object</span><span data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$1.1.0.1">optional</span></p><p style="margin:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$1.1.1">Overrides the inline-styles of the icon element.</p></td></tr><tr data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$2"><td style="padding: 32px 24px 32px 0px; vertical-align: top; position: inherit; font-weight: 500; box-sizing: border-box; min-width: 128px;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$2.0">style</td><td style="padding: 32px 0px; vertical-align: top; width: 100%; border-bottom-style: solid; border-bottom-width: 1px; border-bottom-color: rgb(224, 224, 224); box-sizing: border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$2.1"><p style="margin:0px;font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:0px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$2.1.0"><span style="color:rgba(0, 0, 0, 0.54);padding-right:24px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$2.1.0.0">object</span><span data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$2.1.0.1">optional</span></p><p style="margin:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$2.1.1">Override the inline-styles of the button's root element.</p></td></tr><tr data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$3"><td style="padding: 32px 24px 32px 0px; vertical-align: top; position: inherit; font-weight: 500; box-sizing: border-box; min-width: 128px;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$3.0">tooltip</td><td style="padding: 32px 0px; vertical-align: top; width: 100%; border-bottom-style: solid; border-bottom-width: 1px; border-bottom-color: rgb(224, 224, 224); box-sizing: border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$3.1"><p style="margin:0px;font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:0px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$3.1.0"><span style="color:rgba(0, 0, 0, 0.54);padding-right:24px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$3.1.0.0">string</span><span data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$3.1.0.1">optional</span></p><p style="margin:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$3.1.1">The tooltip text to show.</p></td></tr><tr data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$4"><td style="padding: 32px 24px 32px 0px; vertical-align: top; position: inherit; font-weight: 500; box-sizing: border-box; min-width: 128px;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$4.0">tooltipPosition</td><td style="padding: 32px 0px; vertical-align: top; width: 100%; border-bottom-style: solid; border-bottom-width: 1px; border-bottom-color: rgb(224, 224, 224); box-sizing: border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$4.1"><p style="margin:0px;font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:0px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$4.1.0"><span style="color:rgba(0, 0, 0, 0.54);padding-right:24px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$4.1.0.0">string</span><span data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$4.1.0.1">default: bottom-center</span></p><p style="margin:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$4.1.1">Allows the tooltip to be viewed with different alignments: "bottom-center", "top-center", "bottom-right", "top-right", "bottom-left" and "top-left"</p></td></tr><tr data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$5"><td style="padding: 32px 24px 32px 0px; vertical-align: top; position: inherit; font-weight: 500; box-sizing: border-box; min-width: 128px;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$5.0">tooltipStyles</td><td style="padding: 32px 0px; vertical-align: top; width: 100%; border-bottom-style: solid; border-bottom-width: 1px; border-bottom-color: rgb(224, 224, 224); box-sizing: border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$5.1"><p style="margin:0px;font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:0px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$5.1.0"><span style="color:rgba(0, 0, 0, 0.54);padding-right:24px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$5.1.0.0">object</span><span data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$5.1.0.1">optional</span></p><p style="margin:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$5.1.1">Allows modification of tooltip styles.</p></td></tr><tr data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$6"><td style="padding: 32px 24px 32px 0px; vertical-align: top; position: inherit; font-weight: 500; box-sizing: border-box; min-width: 128px;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$6.0">touch</td><td style="padding: 32px 0px; vertical-align: top; width: 100%; border-bottom-style: none; box-sizing: border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$6.1"><p style="margin:0px;font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:0px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$6.1.0"><span style="color:rgba(0, 0, 0, 0.54);padding-right:24px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$6.1.0.0">bool</span><span data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$6.1.0.1">default: false</span></p><p style="margin:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$0.1.0.$6.1.1">If true, this component will render the touch sized tooltip.</p></td></tr></tbody></table></div><div style="font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:24px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;border-top:solid 1px #e0e0e0;margin-top:24px;" data-reactid=".0.$=12:0.0.0.1:3.$1"><h3 style="font-size:20px;line-height:28px;padding-top:19px;margin-bottom:13px;letter-spacing:0px;font-weight:500;color:rgba(0, 0, 0, 0.87);box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$1.0">Events</h3><table style="border-collapse:collapse;border-spacing:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$1.1"><tbody data-reactid=".0.$=12:0.0.0.1:3.$1.1.0"><tr data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$0"><td style="padding: 32px 24px 32px 0px; vertical-align: top; position: inherit; font-weight: 500; box-sizing: border-box; min-width: 128px;" data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$0.0">onBlur</td><td style="padding: 32px 0px; vertical-align: top; width: 100%; border-bottom-style: solid; border-bottom-width: 1px; border-bottom-color: rgb(224, 224, 224); box-sizing: border-box;" data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$0.1"><p style="margin:0px;font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:0px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$0.1.0"><span data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$0.1.0.1">IconButton.onBlur(e)</span></p><p style="margin:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$0.1.1">Callback function for when the component loses focus.</p></td></tr><tr data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$1"><td style="padding: 32px 24px 32px 0px; vertical-align: top; position: inherit; font-weight: 500; box-sizing: border-box; min-width: 128px;" data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$1.0">onFocus</td><td style="padding: 32px 0px; vertical-align: top; width: 100%; border-bottom-style: none; box-sizing: border-box;" data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$1.1"><p style="margin:0px;font-size:15px;letter-spacing:0px;font-weight:400;line-height:24px;padding-top:0px;margin-bottom:13px;color:rgba(0, 0, 0, 0.87);width:100%;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$1.1.0"><span data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$1.1.0.1">IconButton.onFocus(e)</span></p><p style="margin:0px;box-sizing:border-box;" data-reactid=".0.$=12:0.0.0.1:3.$1.1.0.$1.1.1">Callback function for when the component gains focus.</p></td></tr></tbody></table></div></div>