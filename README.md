storeForm
=========

This bookmarklet lets you save and fill form values, which comes in handy when testing a form that you have to reload repeatedly.

Once you have your form filled in, select this bookmarklet. When you come back to the blank form, select it again and it will populate the controls with the data you saved.

It works with text and textarea, select, checkbox, and radio controls. It doesn't currently work with multiple-select controls... but when's the last time you used one of those?

Once it fills in the fields, you can edit them and select this bookmarklet again to update the saved data - but this only works for text and textarea controls; once you save a checked box or radio button the only way to clear it from the saved data is to open the console and enter the command

    localStorage.removeItem('formData')

which will clear all the saved data.