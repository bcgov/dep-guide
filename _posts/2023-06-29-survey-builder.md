---
title: Survey Builder
date: 2023-08-25 20:55:00 +0800
categories: [pages/features, survey, create, pages]
tags: [survey builder, questions, question types, comments, hidden, template]
pin: true
---

The **Survey Builder** allows you to create and customize surveys from scratch, or edit a clone of an existing survey or template.

Learn more about creating a new survey on the [Create a New Survey](/dep-guide/posts/create-survey/) page or about editing a survey on the [Edit a Survey](/dep-guide/posts/edit-survey/). Once you have created or cloned your survey, or want to edit your survey, you'll do this in the Survey Builder.

![Survey Builder Interface](/assets/UserGuideImages/Images/survey-builder/survey-builder.png)

On the survey builder page, you can edit your survey name by clicking the _edit_ icon next to your survey name.

You can also turn on/off the multi-page option. Please note: if you toggle this option on/off after adding some content, you will lose all the content you created so far (even if you have previously saved your survey).

The left panel includes all the draggable survey components you can choose to add to your survey. The survey platform is built on Form.io, and the component set is the same as what is available in the BC Government's Common HostEd Form Service (CHEFS). This means that the [documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/) for CHEFS components is applicable to the survey components available in the Survey Builder. The one exception is the Postal Code component, which is a custom component specific to DEP. For your convenience, a link to the CHEFS documentation (as well as the Form.io help page, if available) is provided below for each component.

Below the left panel, you will see the options to hide your survey and make your survey a template.

Learn more about hiding a survey on the [Hide a Survey](/dep-guide/posts/hide-a-survey/) page.
Learn more about saving your survey as a template on the [Save Survey as a Template](/dep-guide/posts/save-survey-as-template/) page.

### Survey Component Customization

Survey components are entirely customizable to the needs of your survey. Some surveys may only use one or two components, while others may choose to use all of them.

To start using a component, drag it from the side panel and drop it into your survey workspace.

Each survey component will include settings according to its function. Some components, such as _Text/Images_, will only have a few settings tabs, while components such as radio buttons or checkboxes will have other sections offering more options such as component customization, data validation, and default values.
![Simple and complex component settings](/assets/UserGuideImages/Images/survey-builder/simple-vs-complex-components.png){: .light .shadow .rounded-10}

### Copying components

To copy a component, hover over the component you wish to copy. You will see a set of buttons appear, including a copy button. Click the copy button to select the component you wish to copy. Then, mouse over the component _above_ where you want the new component to be placed. A new button will appear in the row called "Paste below". Click this button to paste the copied component below the selected component.

![Copying and pasting components](/assets/UserGuideImages/Images/survey-builder/copy-paste.png){: .light .shadow .rounded-10}

### Settings

- **Display**: These are settings that modify the front-end UI of a component. The Display setting tab will be the first tab open when editing the component settings.
- **Values**: Values settings relate to how Values are set or how Values are interacted with between fields. Use Values Settings to set a default value or set up data calculation. For example, if you add a question that can be answered with Radio Buttons, you would set the possible answers to your question here. (For example, Yes and No). The label is what will show in your survey. The Value is auto-generated and is what the system will use. If you set a conditional question, you'll use the values to set it up.
- **Validation**: Settings found in the Validation Tab relate directly to the configurable Front-End and Back-End validations for the field. Validation covers settings such as required fields, unique data, min/max requirements, custom validations, and custom error messages.
- **Conditions**: The simple conditional option chooses whether to show a component based on the data input of another field on a form. For example, if the answer to question 1 is "A", display Question B. You can also implement more advanced conditions by using JavaScript. Learn more about JavaScript Validation at the bottom of the page.

- **Logic**: The Logic tab allows you to define custom triggers and actions based on user interactions with the survey components. This can include showing or hiding components, setting values, or executing custom JavaScript functions.

For more information on the component settings, please visit {https://help.form.io/userguide/form-building/component-settings}.

### List of Survey Components

Below is a list of the survey components available in this tool. They are laid out in the same order as they are in the survey builder interface in DEP.

The components are organized into different categories based on their functionality and usage within the survey builder.

The Basic components (under **Basic Layout** and **Basic Fields)** are the foundational building blocks for creating surveys. They include essential elements like text fields, panels, columns, and tabs that are commonly used in most forms.

The Advanced components (under **Advanced Layout** and **Advanced Fields**) provide advanced versions of the basic components, and expose additional customization options and functionalities for more complex survey requirements.
It also contains a few advanced components that are not part of the basic set,
for more complex survey requirements.

The **Advanced Data** and **BC Government** component categories include specialized components that cater to more complex data handling and specific requirements for BC Government surveys.

#### Basic Layout

The Basic Layout section includes commonly used form components such as Text/Images, Columns, Tabs, and Panels. It serves as a solid foundation for designing visually appealing and well-structured forms.

- **Text/Images**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Basic-Layout/#textimages)

- **Columns (2-4)**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Basic-Layout/#columns)

- **Tabs**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Basic-Layout/#tabs)

- **Panel**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Basic-Layout/#panel)

#### Basic Fields

The basic fields in the Form Builder are commonly used in traditional web forms. You'll likely be familiar with these components if you've used a Form Builder before.

- **Text Field**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Basic-Fields/#text-field) / 📖 [Form.io Documentation](https://help.form.io/form-building/basic-components#text-field)

- **Multi-line Text**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Basic-Fields/#multi-line-text) / 📖 [Form.io Documentation](https://help.form.io/form-building/basic-components#multi-line-text)

- **Select List**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Basic-Fields/#select-list) / 📖 [Form.io Documentation](https://help.form.io/form-building/basic-components#select-list)

- **Checkbox**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Basic-Fields/#checkbox) / 📖 [Form.io Documentation](https://help.form.io/form-building/basic-components#check-box)

- **Checkbox Group**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Basic-Fields/#checkbox-group) / 📖 [Form.io Documentation](https://help.form.io/form-building/basic-components#checkbox-group)

- **Radio Group**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Basic-Fields/#radio-group) / 📖 [Form.io Documentation](https://help.form.io/form-building/basic-components#radio)

- **Number**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Basic-Fields/#number) / 📖 [Form.io Documentation](https://help.form.io/form-building/basic-components#number)

- **Email**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Basic-Fields/#email) / 📖 [Form.io Documentation](https://help.form.io/form-building/basic-components#email)

- **Date / Time**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Basic-Fields/#date-time) / 📖 [Form.io Documentation](https://help.form.io/form-building/advance-components#date-and-time)

- **Day**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Basic-Fields/#day) / 📖 [Form.io Documentation](https://help.form.io/form-building/advance-components#day)

- **Postal Code**: Use the Portal Code component to collect the first three characters of a Canadian postal code. This can be used to understand the location of your respondents. Please note: The Digital Engagement Platform does not currently support the display of the locations captured by this component on a map. A third-party software will have to be used to analyze the data collected. Please make sure you have the PIA to collect that information and hide this question from the Public Report on the Report Settings page.

#### Advanced Layout

Layout components in form builders allow users to structure and organize the various elements of a form effectively. They serve distinct purposes in defining the layout and presentation of form fields.

- **HTML Element**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Layout/#html-element) / 📖 [Form.io Documentation](https://help.form.io/form-building/layout-components#html-element)

- **Content**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Layout/#content) / 📖 [Form.io Documentation](https://help.form.io/form-building/layout-components#content)

- **Columns**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Layout/#columns) / 📖 [Form.io Documentation](https://help.form.io/form-building/layout-components#columns)

- **Field Set**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Layout/#field-set) / 📖 [Form.io Documentation](https://help.form.io/form-building/layout-components#field-set)

- **Panel**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Layout/#panel) / 📖 [Form.io Documentation](https://help.form.io/form-building/layout-components#panel)

- **Table**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Layout/#table) / 📖 [Form.io Documentation](https://help.form.io/form-building/layout-components#table)

- **Tabs**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Layout/#tabs) / 📖 [Form.io Documentation](https://help.form.io/form-building/layout-components#tabs)

- **Well**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Layout/#well) / 📖 [Form.io Documentation](https://help.form.io/form-building/layout-components#well)

#### Advanced Fields

Advanced Fields in form builders are an extension of Basic Fields, specifically designed to cater to more complex requirements. They offer additional features, functionality, or customization options beyond what the Basic Components provide.

- **Text Field**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Fields/#text-field) / 📖 [Form.io Documentation](https://help.form.io/form-building/basic-components#text-field)

- **Email**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Fields/#email) / 📖 [Form.io Documentation](https://help.form.io/form-building/basic-components#email)

- **Text Area**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Fields/#text-area) / 📖 [Form.io Documentation](https://help.form.io/form-building/basic-components#text-area)

- **URL**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Fields/#url) / 📖 [Form.io Documentation](https://help.form.io/form-building/advance-components#url)

- **Number**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Fields/#number) / 📖 [Form.io Documentation](https://help.form.io/form-building/basic-components#number)

- **Phone Number**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Fields/#phone-number) / 📖 [Form.io Documentation](https://help.form.io/form-building/advance-components#phone-number)

- **Tags**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Fields/#tags) / 📖 [Form.io Documentation](https://help.form.io/form-building/advance-components#tags)

- **Address**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Fields/#address) / 📖 [Form.io Documentation](https://help.form.io/form-building/advance-components#address)

- **Password**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Fields/#password) / 📖 [Form.io Documentation](https://help.form.io/form-building/advance-components#password)

- **Date/Time**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Fields/#date-time) / 📖 [Form.io Documentation](https://help.form.io/form-building/advance-components#date-and-time)

- **Checkbox**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Fields/#checkbox) / 📖 [Form.io Documentation](https://help.form.io/form-building/basic-components#checkbox)

- **Day**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Fields/#day)

- **Time**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Fields/#time)

- **Select Boxes**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Fields/#select-boxes) / 📖 [Form.io Documentation](https://help.form.io/form-building/basic-components#select-box)

- **Select**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Fields/#select) / 📖 [Form.io Documentation](https://help.form.io/form-building/basic-components#select)

- **Currency**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Fields/#currency) / 📖 [Form.io Documentation](https://help.form.io/form-building/advance-components#currency)

- **Radio**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Fields/#radio) / 📖 [Form.io Documentation](https://help.form.io/form-building/basic-components#radio)

- **Button**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Fields/#button) / 📖 [Form.io Documentation](https://help.form.io/form-building/basic-components#button)

- **Survey** (aka Likert):
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Fields/#survey) / 📖 [Form.io Documentation](https://help.form.io/form-building/advance-components#survey)

- **Signature**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Fields/#signature) / 📖 [Form.io Documentation](https://help.form.io/form-building/advance-components#signature)

#### Advanced Data

Advanced data components are fields that manipulate the way Data is presented, saved, and organized.

- **Hidden**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Data/#hidden) / 📖 [Form.io Documentation](https://help.form.io/form-building/data-components#hidden)

- **Container**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Data/#container) / 📖 [Form.io Documentation](https://help.form.io/form-building/data-components#container)

- **Data Map**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Data/#data-map) / 📖 [Form.io Documentation](https://help.form.io/form-building/data-components#data-map)

- **Data Grid**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Data/#data-grid) / 📖 [Form.io Documentation](https://help.form.io/form-building/data-components#data-grid)

- **Edit Grid**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/Advanced-Data/#edit-grid) / 📖 [Form.io Documentation](https://help.form.io/form-building/data-components#edit-grid)

#### BC Government

- **File Upload**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/BC-Government/#file-upload) / 📖 [Form.io Documentation](https://help.form.io/form-building/premium-components#file)

- **Business Name Search**
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/BC-Government/#business-name-search)

- **Map**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/BC-Government/#map-component)

- **BC Address**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/BC-Government/#bc-address)

- **Simple BC Address**:
  🧑‍🍳 [CHEFS Documentation](https://developer.gov.bc.ca/docs/default/component/chefs-techdocs/Components/Form-Builder/BC-Government/#simple-bc-address)

### Advanced Conditions using Javascript

Most components' conditions can be set without code from the Conditions tab in the Edit modal. You can also use JavaScript to set more advanced conditions. For example, if you want to add conditions based on the value of a Survey Matrix (Likert Scale), JavaScript is the only way to do so, due to the nested structure of the data. Internally, the data look something like this:

```json
{
  // ... other response data
  "likert": {
    "questionOne": "responseValueOne",
    "questionTwo": "responseValueTwo"
  }
  // ... other response data
}
```

As you can see, the `likert` data doesn't just have one value; it contains keys to multiple sub-questions, each with its own data point.

Here is an example of code you can use to add conditions to a Survey.

To add Javascript conditions, open the configuration panel for a component by pressing the "Edit" option (gear icon).

![The Survey component, with the cursor over a small gear icon in the top right. A tooltip over the icon says "Edit".](/assets/UserGuideImages/Images/survey-builder/survey-edit-button.png){: .light .w-75 .shadow .rounded-10 w='1212' h='668'}

![The Survey component's Conditions tab, showing where to add Javascript conditions.](/assets/UserGuideImages/Images/survey-builder/survey-conditions-tab.png){: .light .w-75 .shadow .rounded-10 w='1212' h='668'}

Conditional coding:

We should assign a value to the variable `show` with code, which Form.io will use to determine whether to display the component we are configuring. To access a specific question's current value, use `data.{key}` where `{key}` is the question's key. To get a question's key, click the "API" tab and check the value for "Property Name".

Show a subsequent question if a previous response is not blank or a specific value:

```js
show = data.simpletextfield2 !== "" && data.simpletextfield2 !== "myValue";
```

Show a subsequent question if a single sub-question within a Survey matrix has one of a select number of responses

```js
show = ["responseOption1", "responseOption2", "responseOption3"].includes(
  data.questionKey.subQuestionKey
);
// e.g.
show = ["effective", "veryEffective", "somewhatEffective"].includes(
  data.simplesurveyadvanced1.other
);
```

Show a subsequent question if a single sub-question within a Survey matrix has a given response.

```js
show = data.questionKey.subQuestionKey == "responseOption";
// e.g.
show = data.simplesurveyadvanced2.other == "effective";
```

True when any sub-question has a given set of responses:
Show a subsequent question when any sub-question within a Survey matrix has one of a select number of responses

```js
show = Object.values(data.questionKey).some((value) =>
  ["responseOption1", "responseOption2"].includes(value)
);
// e.g.
show = Object.values(data.simplesurveyadvanced4).some((value) =>
  ["important", "veryImportant"].includes(value)
);
```
